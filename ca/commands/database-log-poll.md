# database:log:poll
Poll the watchdog and print new log entries every x seconds

**Ús:**
```
drupal database:log:poll [arguments] [options]
dblp
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
duration | Duration in seconds which to sleep between database reads

## Exemples
* Print the log entries on screen every x seconds
```
drupal database:log:poll \
  100
```
