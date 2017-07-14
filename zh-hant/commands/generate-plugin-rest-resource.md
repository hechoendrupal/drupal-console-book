# generate:plugin:rest:resource
Generate plugin rest resource

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin Rest Resource class
--name | commands.generate.service.options.name
--plugin-id | Plugin Rest Resource id
--plugin-label | Plugin Rest Resource Label
--plugin-url | Plugin Rest Resource URL
--plugin-states | Plugin Rest Resource States

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
