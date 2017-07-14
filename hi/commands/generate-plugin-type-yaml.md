# generate:plugin:type:yaml
प्लगिन प्रकार युक्त YAML प्रकाशन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन प्रकार क्लास नाम
--plugin-name | प्लगिन प्रकार यांत्रिक नाम
--plugin-file-name | प्लगिन फ़ाइल नाम

## Examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
