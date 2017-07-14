# generate:plugin:type:annotation
Generate a plugin type with annotation discovery

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin type class name
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Plugin type label

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
