# database:restore
Restaurar la estructura y los contenidos de bases de datos y tablas MySQL

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | El nombre de archivo para su archivo de respaldo de la base de datos

## Available arguments
Argument | Details
---------|-------------
database | Clave de la base de datos en el settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
