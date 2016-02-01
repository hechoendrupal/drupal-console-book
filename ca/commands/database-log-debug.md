# database:log:debug
El comandament **database:log:debug** executa Mostrar el registre d'esdeveniments actual de l'aplicació

**Ús:**
```
$ drupal database:log:debug [arguments] [options] 
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--type | Filtrar registre d'esdeveniments per tipus
--severity | Filtrar registre d'esdeveniments per nivell de severitat
--user-id | Filtrar registre d'esdeveniments per ID d'usuari
--reverse | Invertir l'ordre dels esdeveniments
--limit | Limitar el número de resultats
--offset | Punt inicial del límit

## Arguments disponibles
Argument | Detalls
---------|-------------
event-id | ID de l'esdeveniment DBLog
