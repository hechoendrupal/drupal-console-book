# generate:plugin:type:annotation
Genera un tipo de plugin con descubrimiento de anotaciones

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del tipo de plugin
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Etiqueta del tipo de plugin

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
