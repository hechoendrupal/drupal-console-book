# debug:database:log
Exibir eventos de log atuais do aplicativo

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | Limite os resultados a um número específico
--offset | Ponto de partida de um limite
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog evento ID

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
