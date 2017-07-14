# database:dump
Adatbázis szerkezetének és tartalmának kiíratása

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file | Az adatbázis biztonsági mentésének fájlneve
--gz | Pass this option if you want the sql result file gzipped

## Available arguments
Argument | Details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

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
