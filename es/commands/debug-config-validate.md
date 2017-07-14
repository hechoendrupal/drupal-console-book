# debug:config:validate
Función helper para validar una implementación de schema antes de que sea instalado un módulo. Especifique las rutas de archivos de la configuración y el schema como argumentos y se lanzará la validación contra ellos, haciendo el schema más fácil de debugear ahorrando tiempo haciendo instalaciones

**application.gitbook.messages.usage:**
```
drupal debug:config:validate [arguments] [options]
dcv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--schema-name | 

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
filepath | 
schema-filepath | 

## application.gitbook.messages.examples
* 
```
drupal debug:config:validate \
  /path/to/file \
  /path/to/schema-filepath
```
