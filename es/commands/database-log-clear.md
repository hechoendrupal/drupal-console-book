# database:log:clear
Eliminar eventos de la tabla DBLog, filtros disponibles

**Uso:**
```
drupal database:log:clear [arguments] [options]
dblc
dbc
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
* Vaciar el log en la tabla DBLog de la base de datos
```
drupal database:log:clear \
  <database>
```
* Vaciar el log en la tabla DBLog de la base de datos usando filtros
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
