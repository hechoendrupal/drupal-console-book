# database:restore
Restore structure and contents of a database.

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | The filename for your database backup file

## Available arguments
Argument | Details
---------|-------------
database | Database key from settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
