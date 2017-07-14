# database:log:poll
Observar el watchdog e imprimir nuevas entradas en el log cada x segundos

**application.gitbook.messages.usage:**
```
drupal database:log:poll [arguments] [options]
dblp
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filtrar eventos por un tipo específico
--severity | Filtrar eventos por un nivel de severidad específico
--user-id | Filtrar eventos por un id de usuario específico

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
duration | Intervalo en segundos para lectura en la base de datos

## application.gitbook.messages.examples
* Print the log entries on screen every x seconds
```
drupal database:log:poll \
  100
```
