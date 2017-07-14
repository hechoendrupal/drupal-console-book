# debug:database:table
显示数据库所有表

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | settings.php 文件中 Database 的键

## Available arguments
Argument | Details
---------|-------------
table | 调试的数据库表

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
