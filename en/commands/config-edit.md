# config:edit
Change a configuration object with a text editor.

**application.gitbook.messages.usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
config-name | Configuration object name, for example "user.settings".
editor | Editor, for example "vim" or "gedit".

## application.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
