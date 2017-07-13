# database:log:clear
Eliminați evenimentele din tabelul DBLog, sunt disponibile filtre

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:log:clear [arguments] [options]
$ dblc  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
event-id | DBLog event ID

## commands.generate.doc.gitbook.messages.examples
* Clear the database log from DBLog table
```
$ drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
$ drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
