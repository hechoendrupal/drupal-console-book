# generate:plugin:fieldtype
खाना प्रकार प्लगिन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन का क्लास नाम
--label | प्लगिन का उप-शीर्षक
--plugin-id | प्लगिन id
--description | प्लगिन का विवरण
--default-widget | इस प्लगिन का डीफाल्ट खाना विजेट
--default-formatter | इस प्लगिन का डीफाल्ट खाना formatter

## Examples
* Generate a field type plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"
```
* Generate a field type plugin with a default widget and formatter specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"  \
  --default-widget="DefaultWidget"  \
  --default-formatter="DefaultFormatter"
```
