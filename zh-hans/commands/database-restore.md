# database:restore
还原数据库

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:restore [arguments] [options]
$ dbr  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | 数据库备份文件文件名

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | settings.php 文件中 Database 的键

## commands.generate.doc.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
$ drupal database:restore \
  --file='/srv/dump/db.sql'

```
