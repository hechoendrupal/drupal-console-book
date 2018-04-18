# generate:plugin:fieldtype
फील्ड प्रकार प्लगिन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगिन आयडी.
--description | प्लगइन वर्णन.
--default-widget | या प्लगइनचे डीफॉल्ट फील्ड विजेट.
--default-formatter | या प्लगइनची डीफॉल्ट फिल्ड फॉर्मेटर.

## उदाहरणे
* मॉड्यूल नाव, वर्ग, त्याचे लेबल, प्लगिन आयडी आणि वर्णन निर्दिष्ट करणारा एक फील्ड प्रकारचा प्लगिन उत्पन्न करा.
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"
```
* डीफॉल्ट विजेटसह फिल्ड प्रकार प्लगइन उत्पन्न करा आणि फॉर्मेटर मॉड्यूलचे नाव, वर्ग, त्याचे लेबल, प्लगिन आयडी आणि वर्णन निर्दिष्ट करा.
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"  \
  --default-widget="DefaultWidget"  \
  --default-formatter="DefaultFormatter"
```
