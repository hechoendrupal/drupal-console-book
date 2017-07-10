# database:log:poll
Poll the watchdog and print new log entries every x seconds

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:log:poll [arguments] [options]
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
duration | Duration in seconds which to sleep between database reads

## commands.generate.doc.gitbook.messages.examples
* Print the log entries on screen every x seconds
```
$ drupal database:log:poll \
  100

```
