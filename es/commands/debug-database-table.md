# debug:database:table
Muestra todas las tablas de una base de datos dada.

**Uso:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--database | Clave de la base de datos en el settings.php

## Argumentos disponibles
Argumento | Detalles
---------|-------------
table | Tabla a inspeccionar

## Ejemplos
* Mostrar todas las tablas en la base de datos
```
drupal debug:database:table
```
* Mostrar los campos de la tabla de nodo u otra especificada en el argumento
```
drupal debug:database:table node
```
