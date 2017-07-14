# debug:container
Muestra los servicios actuales de la aplicación.

**Usage:**
```
drupal debug:container [arguments] [options]
dco
```

## Available options
Option | Details
-------|-------------
--parameters | Nombre del servicio.

## Available arguments
Argument | Details
---------|-------------
service | Nombre del servicio.
method | Nombre de método.
arguments | Array de argumentos en formato CSV o JSON.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
