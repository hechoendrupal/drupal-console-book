# generate:plugin:field
Génère des plugins de type, de widget et de formateur de champ.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--type-class | Nom de la classe du plugin de type de champ
--type-label | Label du plugin de type de champ
--type-plugin-id | Id du plugin de type de champ
--type-description | Descritpion du plugin de type de champ
--formatter-class | Nom de la classe du plugin de formateur de champ
--formatter-label | label du plugin de formateur de champ
--formatter-plugin-id | Id du plugin de formateur de champ
--widget-class | Nom de la classe du plugin de formateur de champ
--widget-label | Label du plugin de widget de champ
--widget-plugin-id | Id du plugin de widget de champ
--field-type | Type de champ avec lequel les plugins de formateur et de widget peuvent être utilisés
--default-widget | Widget de champ par défaut du plugin de type de champ
--default-formatter | Formateur de champ par défaut du plugin de type de champ

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
