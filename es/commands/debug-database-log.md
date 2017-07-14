# debug:database:log
Desplegar eventos registrados al momento para la aplicación

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## Available options
Option | Details
-------|-------------
--type | Filtrar eventos por un tipo específico
--severity | Filtrar eventos por un nivel de severidad específico
--user-id | Filtrar eventos por un id de usuario específico
--asc | Listar eventos en orden ascendiente
--limit | Limitar los resultados a un número específico
--offset | Punto inicial de un límite
--yml | Imprimir en formato YAML

## Available arguments
Argument | Details
---------|-------------
event-id | ID del evento DBLog

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
