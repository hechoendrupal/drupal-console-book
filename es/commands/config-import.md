# config:import
Importa la configuración del estado actual de la aplicación.

**application.gitbook.messages.usage:**
```
drupal config:import [options]
ci
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Ruta al archivo de configuración que será importado.
--directory | Ruta al directorio de configuración para la importación.
--remove-files | Eliminar archivos tras la sincronización.

## application.gitbook.messages.examples
* Provide a configuration file
```
drupal config:import \
  --file=/path/to/config/file
```
* Provide a configuration directory
```
drupal config:import  \
  --directory=/path/to/config/dir
```
