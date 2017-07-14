# debug:database:log
Affiche les entrées courantes du journal pour l'application

**application.gitbook.messages.usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | Lister les événements par ordre ascendant
--limit | Limiter les résultats à un nombre spécifique
--offset | Point de départ d'une limite
--yml | Print in a yml style

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID de l'événement du DBLog
