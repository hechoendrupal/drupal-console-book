# config:import
Importa la configuración del estado actual de la aplicación.

**Uso:**
```
drupal config:import [options]
ci
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | Ruta a un archivo de configuración para importar.
--directory | Ruta de un directorio de configuración para importar.
--remove-files | Eliminar archivos después de la sincronización.
--skip-uuid | commands.config.import.options.skip-uuid

## Ejemplos
* Facilitando un archivo de configuración
```
drupal config:import \
  --file=/path/to/config/file
```
* Facilitando un directorio de configuración
```
drupal config:import  \
  --directory=/path/to/config/dir
```
