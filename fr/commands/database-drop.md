# database:drop
Supprime toutes les tables d'une base de données.

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | Clé de la base de données du fichier settings.php

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
