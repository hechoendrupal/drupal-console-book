# generate:plugin:fieldformatter
Genera un plugin de formateador de campo.

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--field-type | Tipo de campo con el que el plugin puede ser usado

## Examples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
