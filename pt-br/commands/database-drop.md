# database:drop
Drop all tables in a given database.

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | Database key from settings.php

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
