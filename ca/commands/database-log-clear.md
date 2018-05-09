# database:log:clear
Eliminar esdeveniments de la taula DBLog, filtre disponible

**Ús:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## Arguments disponibles
Argument | Detalls
---------|-------------
event-id | DBLog event ID

## Exemples
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
