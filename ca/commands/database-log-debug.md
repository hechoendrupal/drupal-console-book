# database:log:debug
Mostrar el registre d'esdeveniments actual de l'aplicació

**Ús:**
```
$ drupal database:log:debug [arguments] [options]
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--type | Filtrar registre d'esdeveniments per tipus
--severity | Filtrar el registre d'esdeveniments per nivell de severitat
--user-id | Filtrar el registre d'esdeveniments per identificador d'usuari
--asc | List events in ascending order
--limit | Limitar el número de resultats
--offset | Punt inicial del límit

## Arguments disponibles
Argument | Detalls
---------|-------------
event-id | Identificador de l'esdeveniment DBLog
