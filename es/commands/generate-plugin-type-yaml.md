# generate:plugin:type:yaml
Genera un tipo de plugin con descubrimiento YAML

**Usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del tipo de plugin
--plugin-name | Nombre máquina del tipo de plugin
--plugin-file-name | Nombre del archivo del plugin

## Examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
