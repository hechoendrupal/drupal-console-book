# database:drop
Удалить все таблицы в данной базе данных.

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | Ключ баы данных из settings.php

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
