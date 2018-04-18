# database:log:poll
Poll the watchdog and print new log entries every x seconds

**Utilização:**
```
drupal database:log:poll [arguments] [options]
dblp
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
duration | Duration in seconds which to sleep between database reads

## Exemplos
* Print the log entries on screen every x seconds
```
drupal database:log:poll \
  100
```
