# debug:database:table
Muestra todas las tablas en una base de datos.

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | Clave de la base de datos de settings.php

## Available arguments
Argument | Details
---------|-------------
table | Tabla a depurar

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
