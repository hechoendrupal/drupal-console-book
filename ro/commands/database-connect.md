# database:connect
Lansează un client DB dacă acesta este disponibil

**Usage:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Available arguments
Argument | Details
---------|-------------
database | Cheia bazei de date din fișierul settings.php

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
