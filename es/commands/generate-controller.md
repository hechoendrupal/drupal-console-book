# generate:controller
Generar y registrar un controlador

**Usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del controlador
--routes | Las rutas, debe ser un array conteniendo [título, método, path]
--services | Cargar servicios desde el contenedor.
--test | Generar una clase de prueba

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
