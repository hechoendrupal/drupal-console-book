# generate:plugin:imageformatter
Generar un connector formatador de camp.

**Usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del connector
--label | Etiqueta del connector
--plugin-id | Identificador del connector

## Examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
