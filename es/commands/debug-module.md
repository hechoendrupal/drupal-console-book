# debug:module
Muestra los módulos actualmente disponibles para la aplicación

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | Estado del módulo [installed|uninstalled]
--type | Tipo de módulo [core|no-core]

## Available arguments
Argument | Details
---------|-------------
module | Module name

## Examples
* Muestra todos los módulos habilitados
```
drupal mod --status=installed
```
* Muestra todos los módulos habilitados y que no son del core (contrib + custom)
```
drupal mod --status=installed --type=no-core
```
