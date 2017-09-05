# Setting up your local machine

Using a site alias requires some local configuration.

## Global configuration 

Global configuration can provided using the copied file `~/.console/config.yml`. This information is grouped within the `remote` key.

```
application:
  ...
  remote:
    user: drupal
    port: 22
    options:
    arguments:
    type: ssh
```

## Specific site configuration

Site alias configuration could be provided by adding a YAML file at `/path/to/site/console/sites/sample.yml` or `~/.console/sites/sample.yml` 

```
local:
  root: /var/www/drupal8.dev
  type: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
  type: ssh
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  type: ssh
```

## Debug sites.

All known sites alias can be listed by executing the `debug:site` command.

```
drupal debug:site

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

A site configuration details can be shown by passing the site name as argument to the `debug:site` command. 
```
drupal debug:site sample.dev

user: drupal
port: 22
options:
arguments:
root: /var/www/html/drupal
host: 140.211.10.62
type: ssh
```

**NOTE:** As you may notice the global configuration and the specific site configuration are merged when debugging a site. You can override any global configuration by adding those keys on the site specific configuration.
