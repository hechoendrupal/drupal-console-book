# debug:database:log
Afișează evenimentele curente, de intrare în jurnal, pentru aplicație

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
--limit | Limitați rezultatele la un anumit număr
--offset | Punctul de început al unei limite
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | ID-ul evenimentului DBLog

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
