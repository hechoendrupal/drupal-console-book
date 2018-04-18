# generate:plugin:field
Generează extensiile: tipul de câmp, widget-ul si formatare.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--type-class | Numele clasei extensiei de tip câmp
--type-label | Eticheta extensiei de tip câmp
--type-plugin-id | ID-ul extensiei de tip câmp
--type-description | Descrierea extensiei de tip câmp
--formatter-class | Numele clasei extensiei de formatare a câmpului
--formatter-label | Eticheta extensiei de formatare a câmpului
--formatter-plugin-id | ID-ul extensiei de formatare a câmpului
--widget-class | Numele clasei extensiei de formatare a câmpului
--widget-label | Eticheta extensiei de widget pentru câmp
--widget-plugin-id | ID-ul extensiei de widget pentru câmp
--field-type | Tipul de câmp cu, care pot fi folosite formatarea si widgetul
--default-widget | Widget-ul predefinit al extensiei de tip câmp.
--default-formatter | Formatarea predefinită pentru extensia de tip câmp

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
