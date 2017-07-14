# generate:plugin:fieldformatter
खाना formatter प्लगिन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन क्लास का नाम
--label | प्लगिन उप-शीर्षक
--plugin-id | प्लगिन id
--field-type | खाना प्रकार प्लगिन इस्तेमाल किया जा सकता

## Examples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
