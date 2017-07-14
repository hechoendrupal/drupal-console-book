# database:restore
Restabilește structura și conținutul bazei de date MySQL și ale tabelelor acesteia

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | Numele fișierului pentru backup-ul bazei dvs. de date

## Available arguments
Argument | Details
---------|-------------
database | Cheia bazei de date din fișierul settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
