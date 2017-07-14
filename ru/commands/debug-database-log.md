# debug:database:log
Показать текущий журнал событий приложения

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
--limit | Ограничить количество результатов заданным числом
--offset | Смещение стартовой позиции
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | Идентификатор события в DBLog

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
