# database:restore
还原数据库

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | 数据库备份文件文件名

## Available arguments
Argument | Details
---------|-------------
database | settings.php 文件中 Database 的键

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
