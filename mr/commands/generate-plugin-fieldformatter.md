# generate:plugin:fieldformatter
फील्ड फॉर्मेटर प्लगइन उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगिन आयडी.
--field-type | फील्ड प्रकार प्लगइन सह वापरले जाऊ शकते.

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
