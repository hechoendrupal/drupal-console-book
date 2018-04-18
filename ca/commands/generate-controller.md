# generate:controller
Generar i registrar un controlador

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del controlador
--routes | El camins han de ser matrius i contenir [títol, mètode, camí]
--services | Carregar serveis des del contenidor.
--test | Generar una classe de verificació

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
