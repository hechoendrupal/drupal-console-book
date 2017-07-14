# generate:plugin:field
फील्ड प्रकार, विजेट आणि फॉर्मेटर प्लगइन उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--type-class | फील्ड प्रकार प्लगइन वर्ग नाव.
--type-label | फील्ड प्रकार प्लगइन लेबल.
--type-plugin-id | फील्ड प्रकार प्लगइन आयडी.
--type-description | commands.generate.plugin.field.options.type-type-description
--formatter-class | commands.generate.plugin.field.options.class
--formatter-label | फील्ड फॉर्मेटर प्लगइन लेबल.
--formatter-plugin-id | फील्ड फॉर्मेटर प्लगिन आयडी.
--widget-class | फील्ड फॉर्मेटर प्लगइन वर्ग नाव.
--widget-label | फील्ड विजेट प्लगइन लेबल.
--widget-plugin-id | फील्ड विजेट प्लगइन आयडी.
--field-type | फील्ड प्रकार फॉर्मेटर आणि विजेट प्लगइन सह वापरले जाऊ शकते.
--default-widget | फील्ड प्रकार प्लगइनचे डीफॉल्ट फील्ड विजेट.
--default-formatter | फील्ड प्रकार प्लगइनचे डीफॉल्ट फील्ड फॉर्मेटर.

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
