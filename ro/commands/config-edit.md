# config:edit
Editează configurarea selectată.

**Usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## Available arguments
Argument | Details
---------|-------------
config-name | Numele configurării.
editor | Editor.

## Examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
