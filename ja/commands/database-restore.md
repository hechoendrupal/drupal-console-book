# database:restore
データベースの構造とコンテンツをリストア

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | データベースのバックアップファイルの名前

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | settings.phpのデータベースのキー

## application.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
