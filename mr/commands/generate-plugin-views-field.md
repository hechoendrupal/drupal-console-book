# generate:plugin:views:field
सानुकूल प्लग इन दृश्य फील्ड उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगिन फील्ड श्रेणी नाव दर्शविते.
--title | प्लगिन फील्ड शीर्षक अवलोकने
--description | प्लगिन फील्ड वर्णन पाहते.

## उदाहरणे
* मॉड्यूल नाव, वर्ग, शीर्षक आणि त्याचे वर्णन निर्दिष्ट करणारा सानुकूल दृश्य फील्ड प्लगिन उत्पन्न करा.
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
