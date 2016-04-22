# database:log:clear
Remove events from DBLog table, filters are available

**Usage:**
```
$ drupal database:log:clear [arguments] [options]
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog event ID
