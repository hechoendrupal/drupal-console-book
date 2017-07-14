# generate:plugin:rest:resource
Genera un plugin de recurso rest

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin de recurso rest
--name | commands.generate.service.options.name
--plugin-id | ID del plugin de recurso rest
--plugin-label | Etiqueta del plugin de recurso rest
--plugin-url | URL del plugin de recurso rest
--plugin-states | Estados del plugin de recurso rest

## Examples
* Generate a rest resource plugin using GET specifying the module name, the class, the plugin id, its label, the target url and the request type
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
