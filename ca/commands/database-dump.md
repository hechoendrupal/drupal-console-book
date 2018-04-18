# database:dump
Còpia de seguretat d'estructura, continguts i taules de la base de dades MySQL

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file |  Nom del fitxer de la còpia de la base de dades
--gz | Pass this option if you want the sql result file gzipped

## Available arguments
Argument | Details
---------|-------------
database | Clau de la base de dades des de settings.php

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
