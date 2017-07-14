# database:drop
删除数据库所有表

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | settings.php 文件中 Database 的键

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
