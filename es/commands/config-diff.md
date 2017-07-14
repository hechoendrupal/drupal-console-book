# config:diff
Muestra los items de configuración que son diferentes en la configuración activa comparada con un directorio.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | Ver los cambios inversos (por ejemplo, las diferencias de un directorio frente a la configuración activa).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | El directorio con el que comparar. Si se omite, se elige uno de los directorios de configuración de Drupal.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
