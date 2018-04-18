# generate:plugin:condition
प्लगिन स्थिती उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:condition [options]
gpco
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगिन स्थिती वर्ग नाव.
--label | प्लगिन स्थिती लेबल.
--plugin-id | प्लगिन स्थिती आयडी.
--context-definition-id | संदर्भ व्याख्या आयडी.
--context-definition-label | संदर्भ व्याख्या लेबल.
--context-definition-required | संदर्भ व्याख्या आवश्यक आहे (सत्य / चूक)

## उदाहरणे
* मॉड्यूल नाव, वर्ग, लेबल, आयडी आणि संदर्भ परिभाषित केल्याने नोड करणार्या घटकासाठी प्लगइनची स्थिती उत्पन्न करा.
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:node"  \
  --context-definition-label="node"  \
  --context-definition-required
```
* मॉड्यूल नाव, वर्ग, लेबल, आयडी आणि संदर्भ परिभाषा निर्दिष्ट करणार्या भाषांसाठी प्लगइनची स्थिती उत्पन्न करा.
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="language"  \
  --context-definition-label="Language"  \
  --context-definition-required
```
* मॉड्यूलचे नाव, वर्ग, लेबल, आयडी आणि संदर्भ व्याख्या निर्दिष्ट करणारे रोल कॉन्फिगरेशनसाठी प्लगइन स्थिती उत्पन्न करा.
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:user_role"  \
  --context-definition-label="user_role"  \
  --context-definition-required
```
