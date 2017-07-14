# database:log:clear
Vide la table DBLog contenant les événements, avec possibilité de fitrer

**Usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Available options
Option | Details
-------|-------------
--type | Filtrer les événements selon un type spécifique
--severity | Filtrer les événements selon un niveau spécifique de sévérité
--user-id | Filtrer les événements selon un user id spécifique

## Available arguments
Argument | Details
---------|-------------
event-id | ID de l'événement DBLog

## Examples
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
