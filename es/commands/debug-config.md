# debug:config
Muestra la configuración actual.

**Uso:**
```
$ drupal debug:config [arguments]
$ dc  
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
name | Nombre de la configuración.

## Ejemplos
* List all configuration object names.
```
$ drupal config:debug
```
* Display system site configurations values.
```
$ drupal config:debug system.site
```
* List all system configuration names.
```
$ drupal config:debug | grep system
```
