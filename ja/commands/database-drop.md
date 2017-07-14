# database:drop
データベースから全てのテーブルを削除

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | settings.phpのデータベースのキー

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
