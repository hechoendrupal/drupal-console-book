# generate:plugin:type:yaml
Generează un tip de plugin cu descoperire de YAML.

**Usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei tipului de plugin.
--plugin-name | Numele maşină al tipului de plugin
--plugin-file-name | Numele fişierului tipului de plugin

## Examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
