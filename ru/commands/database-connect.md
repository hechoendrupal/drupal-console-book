# database:connect
Показывает соединение с базой данных

**Usage:**
```
drupal database:connect [arguments]
dbco
```

## Available arguments
Argument | Details
---------|-------------
database | Ключ базы данных из settings.php

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
