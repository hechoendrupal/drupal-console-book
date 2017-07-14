# module:uninstall
Desinstala un módulo o varios en la aplicación

**Usage:**
```
drupal module:uninstall [arguments] [options]
mou
```

## Available options
Option | Details
-------|-------------
--force | ¿ Desea ignorar las dependencias y desinstalar el módulo a la fuerza ?
--composer | Desinstala el módulo mediante Composer

## Available arguments
Argument | Details
---------|-------------
module | Introduzca el nombre del módulo a desinstalar (pulse <return> para detener esta pregunta)

## Examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
