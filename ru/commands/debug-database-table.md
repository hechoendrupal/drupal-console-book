# debug:database:table
Показать все таблицы в данной базе данных.

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | Ключ базы данных из settings.php

## Available arguments
Argument | Details
---------|-------------
table | Таблица для отладки

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
