# database:dump
Dump struktur dan kontan dari basis data

**application.gitbook.messages.usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Nama berkas untuk backup basis data anda
--gz | Pass this option if you want the sql result file gzipped

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Key Basis data dari settings.php

## application.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
drupal database:dump \
  --gz
```
