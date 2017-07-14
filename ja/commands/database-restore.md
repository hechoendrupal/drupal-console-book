# database:restore
データベースの構造とコンテンツをリストア

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | データベースのバックアップファイルの名前

## Available arguments
Argument | Details
---------|-------------
database | settings.phpのデータベースのキー

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
