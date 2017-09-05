# How to use Drupal Console in a remote site installation

Drupal Console allows you to run commands from your local server but actually execute them on a local, remote or virtual (VM, Docker) Drupal installation by using site aliases.

Site aliases are used to provide a collection of predefined options and give them a name.

Site aliases can be executed using the `--target` option and passing the site name you want to interact with.  
```
drupal --target=sample.dev cr all
```

Site aliases can also be executed by using `@` as:
```
drupal @sample.dev cr all
```  

Setting up your local machine to use a site alias requires some configuration.

### Global configuration 
You can provide global configuration to remote connections at the copied file `~/.console/config.yml`. This information is grouped within the `remote` key.
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

### Specific site configuration
You can provide specific site configuration by providing a site alias file at the following paths:

* Global `~/.console/sites/`.
* Per site `/path/to/site/console/sites/`.

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

### Debug sites.
You can list all known sites alias by executing the `debug:site` command.
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

You can show the site configuration details by passing the site name as argument to the `debug:site` command. 
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

## Connecting to a virtual environment
You can connect to a virtual-machine/docker by providing the proper values 
for `extra-options` and `type`.

DrupalVM Example
```
dev:
  root: /var/www/drupalvm/drupal
  host: 192.168.88.88
  user: vagrant
  extra-options: '-o PasswordAuthentication=no -i ~/.vagrant.d/insecure_private_key'
  type: ssh
```
Drupal4Docker example
```
dev:
  root: /var/www/html
  extra-options: docker-compose exec --user=82 php
  type: container
```
When connecting as `type: container` there is no need to provide `host` and `user` values.
 
# Site alias options
Valid key/value options for site alias files.
 
* root: Drupal root project directory.
* host: Domain name of the remote system. Not required on local sites.
* port: The port to use when connecting via shh. The port 22 used by default. 
* user: The username to use when connecting via ssh.
* options: Array of valid DrupalConsole options.
* arguments: Array of valid DrupalConsole arguments.
* extra-options: Used only when the target requires extra options, such as alternative authentication method and/or alternative identity file. 
* type: Type of site to interact with. Allowed options `local`, `ssh`, `container`. The `local` option is used by default.

NOTE: The only required value is `root` since type is defaulted to `local`.
