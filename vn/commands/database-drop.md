# database:drop
Drop tất cả các tables trong 1 cơ sở dữ liệu được đưa ra.

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
