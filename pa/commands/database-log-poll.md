# database:log:poll
Poll the watchdog and print new log entries every x seconds

**application.gitbook.messages.usage:**
```
drupal database:log:poll [arguments] [options]
dblp
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
duration | Duration in seconds which to sleep between database reads

## application.gitbook.messages.examples
* Print the log entries on screen every x seconds
```
drupal database:log:poll \
  100
```
