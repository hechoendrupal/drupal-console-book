# database:connect
Llançar un client de base de dades

**Ús:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Arguments disponibles
Argument | Detalls
---------|-------------
database | Clau de la base de dades des de settings.php

## Exemples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
