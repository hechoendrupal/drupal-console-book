# generate:plugin:field
खाना प्रकार, विजेट और formatter प्लगिन उत्पन्न करें।

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--type-class | खाना प्रकार प्लगिन क्लास का नाम
--type-label | खाना प्रकार प्लगिन उप-शीर्षक
--type-plugin-id | खाना प्रकार प्लगिन id
--type-description | खाना प्रकार प्लगिन विवरण
--formatter-class | खाना formatter प्लगिन क्लास का नाम
--formatter-label | खाना formatter प्लगिन उप-शीर्षक
--formatter-plugin-id | खाना formatter प्लगिन id
--widget-class | खाना formatter प्लगिन क्लास का नाम
--widget-label | खाना विजेट प्लगिन उप-शीर्षक
--widget-plugin-id | खाना विजेट प्लगिन  id
--field-type | खाना प्रकार formatter और विजेट प्लगिन साथ इस्तेमाल किया जा सकता
--default-widget | खाना प्रकार  प्लगिन का डीफाल्ट खाना विजेट
--default-formatter | खाना प्रकार  प्लगिन का डीफाल्ट खाना formatter

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
