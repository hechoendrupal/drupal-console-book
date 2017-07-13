# database:log:clear
Eliminar eventos de la tabla DBLog, filtros disponibles

**Uso:**
```
$ drupal database:log:clear [arguments] [options]
$ dblc  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--type | Filtrar por tipo de evento
--severity | Filtrar eventos por nivel de severidad
--user-id | Filtrar eventos por ID de usuario

## Argumentos disponibles
Argumento | Detalles
---------|-------------
event-id | ID del evento DBLog

## Ejemplos
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
