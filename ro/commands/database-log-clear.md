# database:log:clear
Eliminați evenimentele din tabelul DBLog, sunt disponibile filtre

**application.gitbook.messages.usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | DBLog event ID

## application.gitbook.messages.examples
* Clear the database log from DBLog table
```
drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
