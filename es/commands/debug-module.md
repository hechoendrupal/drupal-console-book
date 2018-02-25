# debug:module
Muestra los módulos actualmente disponibles para la aplicación

**Uso:**
```
drupal debug:module [arguments] [options]
dm
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--status | Estado del módulo [installed|uninstalled]
--type | Tipo de módulo [core|no-core]

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | Nombre del módulo

## Ejemplos
* Muestra todos los módulos habilitados
```
drupal mod --status=installed
```
* Muestra todos los módulos habilitados y que no son del core (contrib + custom)
```
drupal mod --status=installed --type=no-core
```
