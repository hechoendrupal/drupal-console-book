# database:drop
Egy adatbázis összes táblájának eldobása.

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
