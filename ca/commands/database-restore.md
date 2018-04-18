# database:restore
Restaurar l'estructura, continguts i taules de la base de dades MySQL

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | El nom del fitxer de la seva còpia de la base de dades

## Available arguments
Argument | Details
---------|-------------
database | Clau de la base de dades des de settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
