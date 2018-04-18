# generate:plugin:fieldwidget
फिल्ड विजेट प्लगिन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
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
* मॉड्यूलचे नाव, वर्ग, त्याचे लेबल, प्लगिन आयडी आणि फिल्ड प्रकार निर्दिष्ट करणारा मजकूर प्रकार फील्ड विजेट प्लगिन उत्पन्न करा.
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
