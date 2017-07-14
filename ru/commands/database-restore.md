# database:restore
Восстановление структуры и содержимого базы данных

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | Имя файла резервной копии базы данных

## Available arguments
Argument | Details
---------|-------------
database | Ключ базы данных из settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
