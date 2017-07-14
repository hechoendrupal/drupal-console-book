# generate:plugin:field
Generate field type, widget and formatter plugins.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:plugin:field [options]
gpf
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--type-class | Field type plugin class name
--type-label | Field type plugin label
--type-plugin-id | Field type plugin id
--type-description | commands.generate.plugin.field.options.type-type-description
--formatter-class | commands.generate.plugin.field.options.class
--formatter-label | Field formatter plugin label
--formatter-plugin-id | Field formatter plugin id
--widget-class | Field formatter plugin class name
--widget-label | Field widget plugin label
--widget-plugin-id | Field widget plugin id
--field-type | Field type the formatter and widget plugin can be used with
--default-widget | Default field widget of the field type plugin
--default-formatter | Default field formatter of field type plugin

## commands.generate.doc.gitbook.messages.examples
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
