# generate:plugin:rest:resource
प्लगइन उर्वरित संसाधन उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन रेस संसाधन वर्ग.
--name | commands.generate.service.options.name
--plugin-id | प्लगइन प्रवासी संसाधन आयडी
--plugin-label | प्लगइन उर्वरीत संसाधन लेबल.
--plugin-url | प्लगइन उर्वरित संसाधन URL
--plugin-states | प्लगइन रीस्ट रिसोर्स स्टेटस.

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
