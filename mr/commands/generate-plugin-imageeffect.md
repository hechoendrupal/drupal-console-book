# generate:plugin:imageeffect
प्रतिमा प्रभाव प्लगइन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगिन आयडी.
--description | प्लगइन वर्णन.

## उदाहरणे
* मॉड्यूलचे नाव, वर्ग, त्याचे लेबल, प्लगिन आयडी आणि एक वर्णन निर्दिष्ट करणारी प्रतिमा प्रभाव प्लगइन उत्पन्न करा.
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
