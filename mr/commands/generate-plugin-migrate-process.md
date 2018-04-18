# generate:plugin:migrate:process
एक स्थलांतर प्रक्रिया प्लगइन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--plugin-id | प्लगिन आयडी.

## उदाहरणे
* मॉड्यूलचे नाव, वर्ग आणि त्याचेआयडीनिर्दिष्ट करणारे स्थलांतरण प्लगइन उत्पन्न करा.
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
