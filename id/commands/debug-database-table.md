# debug:database:table
Tunjukkan semua tabel dari basis data tertentu.

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | Key basis data dari settings.php

## Available arguments
Argument | Details
---------|-------------
table | Tabel untuk di-debug

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
