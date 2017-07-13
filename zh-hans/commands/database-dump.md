# database:dump
导出数据库

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:dump [arguments] [options]
$ dbdu  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | 数据库备份文件名称
--gz | Pass this option if you want the sql result file gzipped

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | settings.php 文件中 Database 的键

## commands.generate.doc.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
$ drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
$ drupal database:dump \
  --gz
```
