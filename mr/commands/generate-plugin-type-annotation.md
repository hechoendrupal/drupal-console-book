# generate:plugin:type:annotation
भाष्येच्या शोधासह प्लगिन प्रकार उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन प्रकार वर्ग नाव
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | प्लगइन प्रकार लेबल.

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
