# database:log:poll
Poll the watchdog and print new log entries every x seconds

**Usage:**
```
drupal database:log:poll [arguments] [options]
dblp
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
duration | Duration in seconds which to sleep between database reads

## Examples
* Print the log entries on screen every x seconds
```
drupal database:log:poll \
  100
```
