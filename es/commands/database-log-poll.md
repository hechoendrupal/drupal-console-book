# database:log:poll
Observar el watchdog e imprimir nuevas entradas en el log cada x segundos

**Usage:**
```
drupal database:log:poll [arguments] [options]
dblp
```

## Available options
Option | Details
-------|-------------
--type | Filtrar eventos por un tipo específico
--severity | Filtrar eventos por un nivel de severidad específico
--user-id | Filtrar eventos por un id de usuario específico

## Available arguments
Argument | Details
---------|-------------
duration | Intervalo en segundos para lectura en la base de datos

## Examples
* Print the log entries on screen every x seconds
```
drupal database:log:poll \
  100
```
