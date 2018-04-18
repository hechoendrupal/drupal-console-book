# generate:plugin:block
प्लगइन ब्लॉक उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:block [options]
gpb
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव
--label | प्लगइन लेबल
--plugin-id | प्लगिन आयडी
--theme-region | प्लगइन रेंडर करण्यासाठी थीम क्षेत्र.
--inputs | फॉर्म मध्ये इनपुट तयार करा.
--services | कंटेनर मधून सेवा भरा.

## उदाहरणे
* मॉड्यूल नाव, वर्ग, लेबल, आयडी, क्षेत्र आणि इनपुट निर्दिष्ट करणारा इनपुट फील्डसह हेडर क्षेत्रामध्ये एक प्लगइन ब्लॉक उत्पन्न करा.
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
