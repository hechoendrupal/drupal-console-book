# database:restore
Adatbázis szerkezetének és tartalmának visszaállítása.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:restore [arguments] [options]
$ dbr  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | Az adatbázis biztonsági mentésének fájlneve

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## commands.generate.doc.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
$ drupal database:restore \
  --file='/srv/dump/db.sql'

```
