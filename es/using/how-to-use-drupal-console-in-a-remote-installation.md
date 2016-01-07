# How to use Drupal Console in a remote site installation

Drupal Console allows you to run commands on your local server but actually execute them on a remote server.

You can take advantage of this feature, using the `--target` option and passing the remote site name you want to interact with.  
```
$ drupal --target=sample.dev cr all
```

Setting up your local computer to use a remote site requires a little configuration.

### Edit global configuration 
You can provide global configuration to remote connections at the copied file `~/.console/config.yml`. This information is grouped within the `remote` key.
```
application:
  ...
  remote:
    user: root
    port: 22
    console: /usr/local/bin/drupal
    options:
    arguments:
    keys:
      public: ~/.ssh/id_rsa.pub
      private: ~/.ssh/id_rsa
      passphrase: ~/.ssh/passphrase.txt
```

### Edit specific site configuration
You can provide specific site configuration by duplicating the copied site file at `~/.console/sites/sample.yml` with a new same at `~/.console/sites/`.

```
local:
  root: /var/www/drupal8.dev
  host: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  console: /var/www/html/docroot/console.phar
```

### Debug sites.
You can list all known local and remote sites by executing the `site:debug` command.
```
$ drupal site:debug

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

You can show the site configuration details by passing the site name as argument to the `site:debug` command. 
```
$ drupal site:debug sample.dev

user: drupal
port: 22
console: /usr/local/bin/drupal
options:
arguments: 
keys:
    public: ~/.ssh/id_rsa.pub
    private: ~/.ssh/id_rsa
    passphrase: ~/.ssh/passphrase.txt
root: /var/www/html/drupal
host: 140.211.10.62
remote: true
```

**NOTE:** As you may notice the global configuration and the specific site configuration are merged when debugging a site. You can override any global configuration by adding those keys on the site specific configuration.  
