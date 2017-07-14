# database:dump
Dump structure and contents of a database

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file | The filename for your database backup
--gz | Pass this option if you want the sql result file gzipped

## Available arguments
Argument | Details
---------|-------------
database | Database key from settings.php

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
