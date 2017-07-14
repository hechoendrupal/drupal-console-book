# debug:config:validate
Función helper para validar una implementación de schema antes de que sea instalado un módulo. Especifique las rutas de archivos de la configuración y el schema como argumentos y se lanzará la validación contra ellos, haciendo el schema más fácil de debugear ahorrando tiempo haciendo instalaciones

**Usage:**
```
drupal debug:config:validate [arguments] [options]
dcv
```

## Available options
Option | Details
-------|-------------
--schema-name | 

## Available arguments
Argument | Details
---------|-------------
filepath | 
schema-filepath | 

## Examples
* 
```
drupal debug:config:validate \
  /path/to/file \
  /path/to/schema-filepath
```
