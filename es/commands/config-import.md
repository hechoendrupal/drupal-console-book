# config:import
Importa la configuración del estado actual de la aplicación.

**Usage:**
```
drupal config:import [options]
ci
```

## Available options
Option | Details
-------|-------------
--file | Ruta al archivo de configuración que será importado.
--directory | Ruta al directorio de configuración para la importación.
--remove-files | Eliminar archivos tras la sincronización.

## Examples
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
