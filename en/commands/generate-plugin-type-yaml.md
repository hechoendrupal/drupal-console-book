# generate:plugin:type:yaml
Generate a plugin type with Yaml discovery

**Usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin type class name
--plugin-name | Plugin type machine name
--plugin-file-name | Plugin file name

## Examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
