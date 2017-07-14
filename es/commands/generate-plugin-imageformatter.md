# generate:plugin:imageformatter
Genera plugins de formateador de imagen.

**Usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin

## Examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
