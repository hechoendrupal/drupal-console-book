# database:drop
Egy adatbázis összes táblájának eldobása.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:drop [arguments]
$ dbd  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## commands.generate.doc.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
$ drupal database:drop \
  <database>

```
