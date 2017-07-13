# 使用 Drupal Console

Drupal Console 提供两种类型的命令：`标准命令` 和 `容器相关命令`

**标准命令**
能够在 Drupal 8 网站根目录以外的地方运行的命令属于标准命令
 
**容器相关命令**
必须在 Drupal 8 网站根目录内运行的命令属于容器相关命令

### 在 Drupal 网站根目录以外执行 Drupal Console
通过 `--root` 选项指定 Drupal 网站根目录，你就可以在系统中的任何地方运行容器相关命令。
```
$ drupal --root=/var/www/drupal8.dev cr all
```

**NOTE:** Possible messages when executing Drupal Console outside a Drupal site root and no `--root` option provided.

When running the project outside of a Drupal 8 site root, the following message will be shown.  
> In order to list all of the available commands, you should run this inside a drupal root directory.

When running the project within of a Drupal 8 site root, but site is not yet installed, the following message will be shown.
> In order to list all of the available commands you should install drupal first.