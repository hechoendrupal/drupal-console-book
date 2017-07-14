# database:drop
データベースから全てのテーブルを削除

**application.gitbook.messages.usage:**
```
drupal database:drop [arguments]
dbd
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | settings.phpのデータベースのキー

## application.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
