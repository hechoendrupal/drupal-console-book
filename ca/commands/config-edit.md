# config:edit
Editar la configuració seleccionada

**Ús:**
```
drupal config:edit [arguments]
ced
cdit
```

## Arguments disponibles
Argument | Detalls
---------|-------------
config-name | Nom de la configuració
editor | Editor.

## Exemples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
