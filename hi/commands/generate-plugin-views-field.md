# generate:plugin:views:field
विशेष प्लगिन व्यू खाना उत्पन्न करें

**Usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | व्यू प्लगिन खाना क्लास नाम
--title | व्यू प्लगिन खाना शीर्षक
--description | व्यू प्लगिन खाना विवरण

## Examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
