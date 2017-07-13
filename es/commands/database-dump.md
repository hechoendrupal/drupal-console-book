# database:dump
Volcado de la estructura y contenidos de las bases de datos y tablas MySQL

**Uso:**
```
$ drupal database:dump [arguments] [options]
$ dbdu  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file |  Nombre del archivo para el respaldo de la base de datos
--gz | Pase esta opción si desea que el archivo sql resultante sea compimido en formato gz

## Argumentos disponibles
Argumento | Detalles
---------|-------------
database | Clave de la base de datos, desde settings.php

## Ejemplos
* Dump default database or the one specified on the argument
```
$ drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
$ drupal database:dump \
  --gz
```
