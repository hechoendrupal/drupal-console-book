# config:edit
Editar la configuració seleccionada

**Usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## Available arguments
Argument | Details
---------|-------------
config-name | Nom de la configuració
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
