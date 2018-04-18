# database:connect
Megjeleníti az adatbázis-kapcsolatot

**Usage:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Available arguments
Argument | Details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
