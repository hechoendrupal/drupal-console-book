# database:log:clear
Eliminar eventos de la tabla DBLog, filtros disponibles

**application.gitbook.messages.usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filtrar por tipo de evento
--severity | Filtrar eventos por nivel de severidad
--user-id | Filtrar eventos por ID de usuario

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID del evento DBLog

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
