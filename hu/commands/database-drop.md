# database:drop
Egy adatbázis összes táblájának eldobása.

**application.gitbook.messages.usage:**
```
drupal database:drop [arguments]
dbd
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## application.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
