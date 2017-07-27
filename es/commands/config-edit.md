# config:edit
Editar la configuración seleccionada.

**Uso:**
```
drupal config:edit [arguments]
ced
cdit
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
config-name | Nombre de la configuración.
editor | Editor.

## Ejemplos
* Editar la configuración del cron con "vim" (editor por defecto)
```
drupal config:edit system.cron
```
* Editar la configuración del cron con "gedit"
```
drupal config:edit system.cron gedit
```
