# database:restore
Adatbázis szerkezetének és tartalmának visszaállítása.

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | Az adatbázis biztonsági mentésének fájlneve

## Available arguments
Argument | Details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
