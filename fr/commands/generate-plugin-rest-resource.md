# generate:plugin:rest:resource
Génère un plugin de ressource rest

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Classe du plugin de ressource rest
--plugin-id | Id du plugin de la ressource rest
--plugin-label | Label du plugin de la ressource rest
--plugin-url | URL du plugin de la ressource rest
--plugin-states | Etats (States) du plugin de la ressource rest

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
