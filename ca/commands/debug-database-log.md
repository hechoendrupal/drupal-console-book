# debug:database:log
Mostrar el registre d'esdeveniments actual de l'aplicació

**Ús:**
```
drupal debug:database:log [arguments] [options]
dbb
ws
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | Limitar el número de resultats
--offset | Punt inicial del límit
--yml | Print in a yml style

## Arguments disponibles
Argument | Detalls
---------|-------------
event-id | Identificador de l'esdeveniment DBLog

## Exemples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
