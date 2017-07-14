# database:log:clear
Удалить события из таблицы DBLog, фильтры доступны

**Usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Available options
Option | Details
-------|-------------
--type | Отфильтровать события по указанному типу
--severity | Отфильтровать события по указанному уровню важности
--user-id | Отфильтровать события по указанному идентификатору пользователя

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog event ID

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
