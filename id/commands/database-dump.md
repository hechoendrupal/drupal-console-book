# database:dump
Dump struktur dan kontan dari basis data

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file | Nama berkas untuk backup basis data anda
--gz | Pass this option if you want the sql result file gzipped

## Available arguments
Argument | Details
---------|-------------
database | Key Basis data dari settings.php

## Examples
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
