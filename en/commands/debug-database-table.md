# debug:database:table
Show all tables in a given database.

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | Database key from settings.php

## Available arguments
Argument | Details
---------|-------------
table | Table to debug

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
