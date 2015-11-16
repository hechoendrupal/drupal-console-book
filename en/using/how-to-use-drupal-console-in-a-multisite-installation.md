# How to use Drupal Console in a multi-site installation 
 
Drupal Console provides support for Drupal multi-site installations. This project provides the `multisite:debug` command to debug multi-site installations and the `--uri` option to interact with multi-site installations.
 
### How to debug a multi-site installation 
```
$ drupal multisite:debug
```

### How to execute a command against a multi-site installation.
```
$ drupal --uri=http://drupal8.multi.dev cr all
```