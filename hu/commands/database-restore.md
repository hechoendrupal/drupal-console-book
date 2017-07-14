# database:restore
Adatbázis szerkezetének és tartalmának visszaállítása.

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Az adatbázis biztonsági mentésének fájlneve

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## application.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
