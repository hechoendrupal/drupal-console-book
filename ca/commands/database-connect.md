# database:connect
Llançar un client de base de dades

**Usage:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Available arguments
Argument | Details
---------|-------------
database | Clau de la base de dades des de settings.php

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
