# config:edit
Change a configuration object with a text editor.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal config:edit [arguments]
ced
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
config-name | Configuration object name, for example "user.settings".
editor | Editor, for example "vim" or "gedit".

## commands.generate.doc.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
