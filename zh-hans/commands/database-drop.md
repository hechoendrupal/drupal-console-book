# database:drop
删除数据库所有表

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:drop [arguments]
$ dbd  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | settings.php 文件中 Database 的键

## commands.generate.doc.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
$ drupal database:drop \
  <database>

```
