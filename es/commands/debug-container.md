# debug:container
Muestra los servicios actuales de la aplicación.

**Uso:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--parameters | Nombre del servicio.

## Argumentos disponibles
Argumento | Detalles
---------|-------------
service | Nombre del servicio.
method | Nombre del método.
arguments | Array de argumentos en formato CSV o JSON.

## Ejemplos
* Mostrar los servicios views.views_data_helper
```
drupal debug:container views.views_data_helper
```
