# generate:update
hook_update_N() चा अंमलबजावणी उत्पन्न करा.

**Usage:**
```
drupal generate:update [options]
gu
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--update-n | नंबर अद्यतनित करा.

## Examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
