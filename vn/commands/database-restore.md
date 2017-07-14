# database:restore
Khôi phục cấu trúc và content của một cơ sở dữ liệu

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Tên cho tệp sao lưu cơ sở dữ liệu của bạn

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Khoá cơ sở dữ liệu từ tệp settings.php

## application.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
