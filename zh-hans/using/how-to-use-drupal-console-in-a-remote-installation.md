# Drupal Console 用于非本地网站

Drupal Console 允许在本地运行命令，但命令的实际执行却是在一个远程服务器上。

我们可以利用这个功能，使用 `--target` 选项，指定想要交互的远程服务器上的网站
```
$ drupal --target=sample.dev cr all
```

使用这个功能需要一点配置

### 编辑全局配置
你可以在 `~/.console/config.yml` 文件中提供全局配置，来进行远程连接。相关配置信息属于 `remote` 这个键.
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

### 编辑特定网站的配置
你可以复制一份 `~/.console/sites/sample.yml` ，包含一个新站点的配置放到 `~/.console/sites/` 

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
