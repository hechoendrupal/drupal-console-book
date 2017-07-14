# database:restore
Mengembalikan struktur dan konten sebuah basis data.

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | Nama file backup basis data anda

## Available arguments
Argument | Details
---------|-------------
database | Key basis data dari settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
