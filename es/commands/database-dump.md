# database:dump
Volcado de la estructura y contenidos de las bases de datos y tablas MySQL

**application.gitbook.messages.usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file |  Nombre del archivo para el respaldo de la base de datos
--gz | Pase esta opción si desea que el archivo sql resultante sea compimido en formato gz

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Clave de la base de datos, desde settings.php

## application.gitbook.messages.examples
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
