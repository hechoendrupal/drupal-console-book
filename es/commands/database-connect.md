# database:connect
Lanzar un cliente de base de datos si está disponible

**Uso:**
```
drupal database:connect [arguments]
dbco
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
database | Clave de base de datos, desde settings.php

## Ejemplos
* Conectar a una base de datos especificada, o a la por defecto si no se pasaran argumentos
```
drupal database:connect \
  <database>
```
