# debug:config:validate
Función helper para validar una implementación de schema antes de que sea instalado un módulo. Especifique las rutas de archivos de la configuración y el schema como argumentos y se lanzará la validación contra ellos, haciendo el schema más fácil de debugear ahorrando tiempo haciendo instalaciones

**Uso:**
```
$ drupal debug:config:validate [arguments] [options]
$ dcv  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--schema-name | 

## Argumentos disponibles
Argumento | Detalles
---------|-------------
filepath | 
schema-filepath | 

## Ejemplos
* 
```
$ drupal debug:config:validate \
  /path/to/file \
  /path/to/schema-filepath

```
