# config:edit
Edit the selected configuration.

**application.gitbook.messages.usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
config-name | Configuration name.
editor | Editor.

## application.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
