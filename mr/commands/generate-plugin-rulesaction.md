# generate:plugin:rulesaction
प्लगिन नियम क्रिया उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगइन आयडी
--type | क्रिया प्रकार (वापरकर्ता किंवा नोड)
--category | प्लगइन श्रेणी
--context | प्लगइन संदर्भ

## उदाहरणे
* मॉड्यूल नाव, वर्ग, त्याचे लेबल, प्लगिन id, प्रकार, श्रेणी आणि त्याचे संदर्भ निर्दिष्ट करणारा वापरकर्ता नियम कृती प्लगिन उत्पन्न करा.
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="user"  \
  --category="default_action"  \
  --context="default_action"
```
* मॉड्यूल नाव, वर्ग, त्याचे लेबल, प्लगिन आयडी, प्रकार, श्रेणी आणि त्याचे संदर्भ निर्दिष्ट करणारे नोड नियत कार्य प्लगइन उत्पन्न करा.
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="node"  \
  --category="default_action" \
  --context="default_action"
```
