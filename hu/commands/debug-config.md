# debug:config
Aktuális konfiguráció megjelenítése.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:config [arguments]
$ dc  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | A konfiguráció neve.

## commands.generate.doc.gitbook.messages.examples
* List all configuration object names.
```
$ drupal config:debug
```
* Display system site configurations values.
```
$ drupal config:debug system.site
```
* List all system configuration names.
```
$ drupal config:debug | grep system
```
