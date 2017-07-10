# database:log:clear
Remove events from DBLog table, filters are available

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:log:clear [arguments] [options]
$ dbc  
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
