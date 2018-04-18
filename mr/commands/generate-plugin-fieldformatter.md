# generate:plugin:fieldformatter
फील्ड फॉर्मेटर प्लगइन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगिन आयडी.
--field-type | फील्ड प्रकार प्लगइन सह वापरले जाऊ शकते.

## उदाहरणे
* मॉड्यूल नाव, वर्ग, लेबलचे प्लगिनआयडीआणि फील्ड प्रकार निर्दिष्ट करणारा एक मजकूर फील्ड फॉर्मेटर प्लगिन उत्पन्न करा.
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
