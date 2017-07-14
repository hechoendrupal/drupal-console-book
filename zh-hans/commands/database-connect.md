# database:connect
如果有数据库客户端，启动它

**Usage:**
```
drupal database:connect [arguments]
dbco
```

## Available arguments
Argument | Details
---------|-------------
database | settings.php 文件中 Database 的键

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
