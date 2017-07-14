# database:log:clear
Vide la table DBLog contenant les événements, avec possibilité de fitrer

**application.gitbook.messages.usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filtrer les événements selon un type spécifique
--severity | Filtrer les événements selon un niveau spécifique de sévérité
--user-id | Filtrer les événements selon un user id spécifique

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID de l'événement DBLog

## application.gitbook.messages.examples
* Clear the database log from DBLog table
```
drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
