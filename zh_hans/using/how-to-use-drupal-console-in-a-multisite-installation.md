# 如何在多站点环境下使用 Drupal Console

对 Drupal 的多站点（多个站点共用一个Drupal核心）Drupal Console 提供了支持。`multisite:debug` 命令和 `--uri` 选项被用于与多站点进行交互。

 
### 列出多站点
```
$ drupal multisite:debug

+---------------------+--------------------------------+
| Site                | Directory                      |
+---------------------+--------------------------------+
| drupal8.dev         | /var/www/drupal8.dev/default   |
| drupal8.multi.dev   | /var/www/drupal8.dev/multi.dev |
+---------------------+--------------------------------+

表示一个网站使用的格式: <端口>.<域名>.<路径>
```

### 针对某个多站点中的某个站点，执行命令
```
$ drupal --uri=http://drupal8.multi.dev cr all
```
