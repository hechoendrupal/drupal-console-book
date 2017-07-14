# config:edit
Szerkeszteni kell a kiválasztott konfigurációt.

**application.gitbook.messages.usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
config-name | A konfiguráció neve.
editor | Szerkesztő.

## application.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
