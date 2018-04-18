# generate:plugin:rest:resource
REST-erőforrás bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | REST-erőforrás bővítményosztály
--plugin-id | REST-erőforrás bővítmény azonosítója
--plugin-label | REST-erőforrás bővítmény címkéje
--plugin-url | REST-erőforrás bővítmény URL-címe
--plugin-states | REST-erőforrás bővítmény állapotok

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
