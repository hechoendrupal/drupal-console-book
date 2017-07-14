# config:export:view
अन्य वेबसाइट में पुन: उपयोग करने के लिए एक प्रोवाइडेड मॉड्यूल के अंदर YAML फॉर्मेट में एक व्यू एक्सपोर्ट करे।

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | अपने मॉड्यूल में एक वैकल्पिक YAML कॉन्फ़िगरेशन के रूप में व्यू एक्सपोर्ट करे
--include-module-dependencies | मॉड्यूल इन्फो YAML फाइल में व्यू मॉड्यूल निर्भरता को शामिल करें

## Available arguments
Argument | Details
---------|-------------
view-id | व्यू आईडी

## Examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
