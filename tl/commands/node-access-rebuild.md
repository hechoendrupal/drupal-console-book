# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**application.gitbook.messages.usage:**
```
drupal node:access:rebuild [options]
nar
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--batch | Process in batch mode.

## application.gitbook.messages.examples
* Rebuild node access permissions
```
drupal node:access:rebuild --batch
```
