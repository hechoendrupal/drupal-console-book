# How to use Drupal Console in a multi-site installation 
 
Drupal Console provides support for Drupal multi-site installations. This project provides the `multisite:debug` command to debug multi-site installations and the `--uri` option to interact with multi-site installations.
 
### How to list all known multi sites
```
$ drupal multisite:debug

+---------------------+--------------------------------+
| Site                | Directory                      |
+---------------------+--------------------------------+
| drupal8.dev         | /var/www/drupal8.dev/default   |
| drupal8.multi.dev   | /var/www/drupal8.dev/multi.dev |
+---------------------+--------------------------------+

 Sites are written using the format: <port>.<domain>.<path>
```

### How to execute a command against a multi-site installation
```
$ drupal --uri=http://drupal8.multi.dev cr all
```
