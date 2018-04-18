# generate:plugin:rest:resource
Generează un plugin de tip resursă REST

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Clasa pluginului de tip resursă REST
--plugin-id | Id-ul pluginului de tip resursă REST
--plugin-label | Eticheta pluginului de tip resursă REST
--plugin-url | URL-ul pluginului de tip resursă REST
--plugin-states | Stările pluginului de tip resursă REST

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
