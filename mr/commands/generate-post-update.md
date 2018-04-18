# generate:post:update
Hook_post_update_NAME() चा अंमलबजावणी उत्पन्न करा.

**वापर:**
```
drupal generate:post:update [options]
gpu
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--post-update-name | पोस्ट अद्यतन नाव.

## उदाहरणे
* मॉड्यूलचे नाव आणि पोस्ट अपडेट नाव दर्शविणारी पोस्ट अपडेट हुक अंमलबजावणी उत्पन्न करा.
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
