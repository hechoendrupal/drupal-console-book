# database:dump
Dump cấu trúc và nội dung của 1 cơ sở dữ liệu

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:dump [arguments] [options]
$ dbdu  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file |  Tên file cho database backup của bạn
--gz | Pass this option if you want the sql result file gzipped

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Database key từ settings.php

## commands.generate.doc.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
$ drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
$ drupal database:dump \
  --gz
```
