# config:import
Importa la configuración del estado actual de la aplicación.

**Uso:**
```
$ drupal config:import [options]
$ ci  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | Ruta al archivo de configuración que será importado.
--directory | Ruta al directorio de configuración para la importación.
--remove-files | Eliminar archivos tras la sincronización.

## Ejemplos
* Provide a configuration file
```
$ drupal config:import \
  --file=/path/to/config/file
```
* Provide a configuration directory
```
$ drupal config:import  \
  --directory=/path/to/config/dir

```
