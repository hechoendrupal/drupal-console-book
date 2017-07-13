# database:connect
如果有数据库客户端，启动它

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:connect [arguments]
$ dbco  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | settings.php 文件中 Database 的键

## commands.generate.doc.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
$ drupal database:connect \
  <database>

```
