# generate:plugin:field
Mezőtípus, felületi elem és formázó bővítmények létrehozása.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--type-class | Mezőtípus bővítmény osztályneve
--type-label | Mezőtípus bővítmény felirata
--type-plugin-id | Mezőtípus bővítmény azonosítója
--type-description | Mezőtípus bővítmény leírása
--formatter-class | Mezőformázó bővítmény osztályneve
--formatter-label | Mezőformázó bővítmény felirata
--formatter-plugin-id | Mezőformázó bővítmény azonosítója
--widget-class | Mezőformázó bővítmény osztályneve
--widget-label | Mező felületi elem bővítmény felirata
--widget-plugin-id | Mező felületi elem bővítmény azonosítója
--field-type | Mezőtípus, amivel a formázó és a felületi elem bővítmény használható
--default-widget | A mezőtípus bővítmény alapértelmezett mező felületi eleme
--default-formatter | A mezőtípus bővítmény alapértelmezett mezőformázójatype plugin

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
