# generate:entity:bundle
नवीन सामग्री प्रकार उत्पन्न करा (नोड / संस्था बंडल)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--bundle-name | सामग्रीचे प्रकारचे मशीन नाव.
--bundle-title | सामग्री प्रकारचे मानवी-वाचनीय नाव.

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
