# config:edit
Editar la configuración seleccionada.

**Uso:**
```
$ drupal config:edit [arguments]
$ ced  
$ cdit  
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
config-name | Nombre de la configuración.
editor | Editor.

## Ejemplos
* Edit system cron configurations with "vim" (default editor).
```
$ drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
$ drupal config:edit system.cron gedit
```
