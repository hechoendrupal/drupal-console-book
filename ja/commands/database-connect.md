# database:connect
データベースクライアントを起動

**Usage:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Available arguments
Argument | Details
---------|-------------
database | settings.phpのデータベースのキー

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
