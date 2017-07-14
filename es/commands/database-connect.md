# database:connect
Lanzar un cliente de base de datos si está disponible

**Usage:**
```
drupal database:connect [arguments]
dbco
```

## Available arguments
Argument | Details
---------|-------------
database | Clave de base de datos, desde settings.php

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
