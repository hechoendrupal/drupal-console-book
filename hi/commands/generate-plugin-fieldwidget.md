# generate:plugin:fieldwidget
खाना विजेट प्लगिन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन का क्लास नाम
--label | प्लगिन का उप-शीर्षक
--plugin-id | प्लगिन id
--field-type | खाना प्रकार प्लगिन इस्तेमाल किया जा सकता

## Examples
* Generate a text type field widget plugin specifying the module name, the class, its label, the plugin id and the field type
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
