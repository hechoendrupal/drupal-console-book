# database:connect
Megjeleníti az adatbázis-kapcsolatot

**application.gitbook.messages.usage:**
```
drupal database:connect [arguments]
dbco
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## application.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
