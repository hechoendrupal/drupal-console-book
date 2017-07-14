# generate:plugin:type:annotation
प्लगिन प्रकार युक्त अननोटेशन प्रकाशन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन प्रकार क्लास नाम
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | प्लगिन प्रकार उप-शीर्षक

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
