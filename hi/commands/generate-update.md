# generate:update
Generate an implementation of hook_update_N()

**Usage:**
```
drupal generate:update [options]
gu
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--update-n | Update Number

## Examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
