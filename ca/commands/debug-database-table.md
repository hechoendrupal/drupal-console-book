# debug:database:table
Mostrar les taules d'una base de dades.

**Ús:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--database | Database key from settings.php

## Arguments disponibles
Argument | Detalls
---------|-------------
table | Table to debug

## Exemples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
