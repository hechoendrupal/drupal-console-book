# database:restore
Khôi phục cấu trúc và content của một cơ sở dữ liệu

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | Tên cho tệp sao lưu cơ sở dữ liệu của bạn

## Available arguments
Argument | Details
---------|-------------
database | Khoá cơ sở dữ liệu từ tệp settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
