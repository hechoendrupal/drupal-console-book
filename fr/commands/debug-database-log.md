# debug:database:log
Affiche les entrées courantes du journal pour l'application

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
ws
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | Lister les événements par ordre ascendant
--limit | Limiter les résultats à un nombre spécifique
--offset | Point de départ d'une limite
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | ID de l'événement du DBLog

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
