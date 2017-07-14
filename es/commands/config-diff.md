# config:diff
Muestra los items de configuración que son diferentes en la configuración activa comparada con un directorio.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | Ver los cambios inversos (por ejemplo, las diferencias de un directorio frente a la configuración activa).

## Available arguments
Argument | Details
---------|-------------
directory | El directorio con el que comparar. Si se omite, se elige uno de los directorios de configuración de Drupal.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
