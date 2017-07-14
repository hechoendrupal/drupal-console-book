# generate:plugin:views:field
सानुकूल प्लग इन दृश्य फील्ड उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगिन फील्ड श्रेणी नाव दर्शविते.
--title | प्लगिन फील्ड शीर्षक अवलोकने
--description | प्लगिन फील्ड वर्णन पाहते.

## Examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
