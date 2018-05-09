# database:restore
Restaurar l'estructura, continguts i taules de la base de dades MySQL

**Ús:**
```
drupal database:restore [arguments] [options]
dbr
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--file | El nom del fitxer de la seva còpia de la base de dades

## Arguments disponibles
Argument | Detalls
---------|-------------
database | Clau de la base de dades des de settings.php

## Exemples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
