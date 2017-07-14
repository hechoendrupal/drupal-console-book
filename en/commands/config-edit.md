# config:edit
Change a configuration object with a text editor.

**Usage:**
```
drupal config:edit [arguments]
ced
```

## Available arguments
Argument | Details
---------|-------------
config-name | Configuration object name, for example "user.settings".
editor | Editor, for example "vim" or "gedit".

## Examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
