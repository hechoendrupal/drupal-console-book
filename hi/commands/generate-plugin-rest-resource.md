# generate:plugin:rest:resource
प्लगिन रेस्ट साधन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन रेस्ट साधन क्लास
--plugin-id | प्लगिन रेस्ट साधन
--plugin-label | प्लगिन रेस्ट साधन उप-शीर्षक
--plugin-url | प्लगिन रेस्ट साधन URL
--plugin-states | प्लगिन रेस्ट साधन स्थिति

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
