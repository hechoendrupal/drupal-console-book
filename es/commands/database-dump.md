# database:dump
Volcado de la estructura y contenidos de las bases de datos y tablas MySQL

**Uso:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | Nombre del archivo para el respaldo de la base de datos
--gz | Pase esta opción si desea el archivo de resultado sql comprimido con gzip

## Argumentos disponibles
Argumento | Detalles
---------|-------------
database | Clave de la base de datos, desde settings.php

## Ejemplos
* Volcar la base de datos por defecto o la especificada como argumento
```
drupal database:dump \
  <database>
```
* Volcar en formato comprimido con gzip
```
drupal database:dump \
  --gz
```
