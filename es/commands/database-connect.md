# database:connect
Lanzar un cliente de base de datos si está disponible

**Uso:**
```
$ drupal database:connect [arguments]
$ dbco  
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
database | Clave de base de datos, desde settings.php

## Ejemplos
* Connects to an specified database, or the default if not arguments passed
```
$ drupal database:connect \
  <database>

```
