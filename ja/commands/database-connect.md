# database:connect
データベースクライアントを起動

**application.gitbook.messages.usage:**
```
drupal database:connect [arguments]
dbco
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | settings.phpのデータベースのキー

## application.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
