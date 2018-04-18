# generate:update
hook_update_N() चा अंमलबजावणी उत्पन्न करा.

**वापर:**
```
drupal generate:update [options]
gu
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--update-n | नंबर अद्यतनित करा.

## उदाहरणे
* मॉड्यूल नाव आणि N मूल्य निर्दिष्ट करणारा अद्यतन हुक कार्यान्वयन उत्पन्न करा.
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
