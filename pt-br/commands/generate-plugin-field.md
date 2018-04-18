# generate:plugin:field
Gera plugins de widgets, fortmato e tipo de campo

**Utilização:**
```
drupal generate:plugin:field [options]
gpf
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--type-class | Nome da classe do plugin de tipo de campo
--type-label | Label do plugin de tipo de campo
--type-plugin-id | ID do plugin de tipo de campo
--type-description | Descrição do plugin de tipo de campo
--formatter-class | Nome da classe do plugin de formato de campo
--formatter-label | Label do plugin de formato de campo
--formatter-plugin-id | ID do plugin de formato de campo
--widget-class | Nome da classe do plugin de formato de campo
--widget-label | Label do plugin de widget de campo
--widget-plugin-id | ID do plugin de widget de campo
--field-type | Tipo de campo, formato e plugin widget que pode ser usado
--default-widget | Widget de campo padrão do plugin tipo de campo
--default-formatter | Formatador de campo padrão do plugin tipo de campo

## Exemplos
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
