# debug:database:log
Az alkalmazás aktuális naplóeseményeinek megjelenítése

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
--asc | List events in ascending order
--limit | Egy adott számra korlátozza a találatok számát
--offset | Egy korlát kezdőpontja
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog eseményazonosító

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
