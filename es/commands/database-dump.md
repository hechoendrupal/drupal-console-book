# database:dump
Volcado de la estructura y contenidos de las bases de datos y tablas MySQL

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file |  Nombre del archivo para el respaldo de la base de datos
--gz | Pase esta opción si desea que el archivo sql resultante sea compimido en formato gz

## Available arguments
Argument | Details
---------|-------------
database | Clave de la base de datos, desde settings.php

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
