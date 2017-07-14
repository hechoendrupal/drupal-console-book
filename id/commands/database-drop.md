# database:drop
Hapus semua tabel pada basis data terpilih.

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | Key basis data pada settings.php

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
