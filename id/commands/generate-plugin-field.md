# generate:plugin:field
Hasilkan tipe, widget, dan plugin pemformat untuk field.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--type-class | Nama kelas plugin tipe field
--type-label | Label plugin tipe field
--type-plugin-id | ID plugin tipe field
--type-description | commands.generate.plugin.field.options.type-type-description
--formatter-class | commands.generate.plugin.field.options.class
--formatter-label | Label plugin pemformat field
--formatter-plugin-id | ID plugin pemformat field
--widget-class | Nama kelas plugin pemformat field
--widget-label | Label plugin field widget
--widget-plugin-id | ID plugin field widget
--field-type | Tipe field yang dapat digunakan dengan plugin pemformat dan widget
--default-widget | field widget bawaan dari plugin tipe field
--default-formatter | Formatter field bawaan dari plugin tipe field

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
