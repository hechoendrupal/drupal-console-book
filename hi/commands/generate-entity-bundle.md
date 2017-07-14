# generate:entity:bundle
एक नया कंटेंट प्रकार उत्पन्न करें (नोड/एंटिटी बंडल)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--bundle-name | कंटेंट प्रकार का यांत्रिक नाम
--bundle-title | कंटेंट प्रकार का मानव पठनीय नाम

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
