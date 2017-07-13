# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal node:access:rebuild [options]
$ nar  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--batch | Process in batch mode.

## commands.generate.doc.gitbook.messages.examples
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
