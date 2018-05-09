# database:restore
Restaure la structure et le contenu de votre base de données MySQL depuis une sauvegarde

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | Le nom du fichier de votre sauvegarde de base de données

## Available arguments
Argument | Details
---------|-------------
database | Clé de la base de données du fichier settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
