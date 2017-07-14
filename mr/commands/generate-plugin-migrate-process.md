# generate:plugin:migrate:process
एक स्थलांतर प्रक्रिया प्लगइन उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--plugin-id | प्लगिन आयडी.

## Examples
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
