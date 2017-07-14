# database:log:clear
Eliminar eventos de la tabla DBLog, filtros disponibles

**Usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Available options
Option | Details
-------|-------------
--type | Filtrar por tipo de evento
--severity | Filtrar eventos por nivel de severidad
--user-id | Filtrar eventos por ID de usuario

## Available arguments
Argument | Details
---------|-------------
event-id | ID del evento DBLog

## Examples
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
