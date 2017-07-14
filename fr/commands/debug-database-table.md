# debug:database:table
Montre toutes les tables d'une base de données spécifique.

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | Clé de la base de données du fichier settings.php

## Available arguments
Argument | Details
---------|-------------
table | Table à débugger

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
