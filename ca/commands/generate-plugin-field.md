# generate:plugin:field
Generar connectors de tipus de camp, giny i formatador de connectors

**Ús:**
```
drupal generate:plugin:field [options]
gpf
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--type-class | Nom de la classe del connector de tipus de camp
--type-label | Etiqueta del connector de tipus de camp
--type-plugin-id | Identificador del connector de tipus de camp
--type-description | Descripció del connector del tipus de camp
--formatter-class | Nom de la classe del connector de formatador de camp
--formatter-label | Etiqueta del connector de formatador de camp
--formatter-plugin-id | Identificador del connector de formatador de camp
--widget-class | Nom de la classe del connector de formatador de camp
--widget-label | Etiqueta del connector del giny
--widget-plugin-id | Identificador del connector del giny
--field-type | Tipus de camp del formatador i connector del giny amb el que pot ser utilitzat
--default-widget | Giny de camp predeterminat del connector de tipus de camp
--default-formatter | Formatador de camp predeterminat del connector de tipus de camp

## Exemples
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
