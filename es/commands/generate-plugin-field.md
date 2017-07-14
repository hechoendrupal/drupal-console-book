# generate:plugin:field
Genera plugins de widget, formateador y tipo de campo.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--type-class | Nombre de clase del plugin de tipo de campo
--type-label | Etiqueta del plugin de tipo de campo
--type-plugin-id | ID del plugin de tipo de campo
--type-description | commands.generate.plugin.field.options.type-type-description
--formatter-class | commands.generate.plugin.field.options.class
--formatter-label | Etiqueta del plugin de formateador de campo
--formatter-plugin-id | ID del plugin de formateador de campo
--widget-class | Nombre de clase del plugin de formateador de campo
--widget-label | Etiqueta del plugin de widget de campo
--widget-plugin-id | ID del plugin de widget de campo
--field-type | Plugin de tipo de campo, formateador y widget con el que puede ser usado
--default-widget | Widget de campo por defecto del plugin de tipo de campo
--default-formatter | Formateador de campo por defecto del plugin de tipo de campo

## Examples
* Generate field type, widget and formatter plugins specifying the module name, the type (class, label, plugin id and description), the formatter (class, label, plugin id) and the widget (class, label and plugin id)
```
drupal generate:plugin:field  \
  --module="modulename"  \
  --type-class="ExampleFieldType"  \
  --type-label="Example field type"  \
  --type-plugin-id="example_field_type"  \
  --type-description="My Field Type"  \
  --formatter-class="ExampleFormatterType"  \
  --formatter-label="Example formatter type"  \
  --formatter-plugin-id="example_formatter_type"  \
  --widget-class="ExampleWidgetType"  \
  --widget-label="Example widget type"  \
  --widget-plugin-id="example_widget_type"  \
  --field-type="example_field_type"  \
  --default-widget="example_widget_type"  \
  --default-formatter="example_formatter_type"
```
