# database:log:debug
Display current log events for the application

**Usage:**
```
$ drupal database:log:debug [arguments] [options]
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | Limit results to a specific number
--offset | Starting point of a limit

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog event ID
