# generate:plugin:rest:resource
Tạo plugin rest resource

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Lớp plugin rest resource
--plugin-id | Plugin Rest Resource id
--plugin-label | Nhãn Plugin Rest Resource
--plugin-url | Plugin Rest Resource URL
--plugin-states | Tình trạng Plugin Rest Resource

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
