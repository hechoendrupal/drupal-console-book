# generate:plugin:migrate:source
माइग्रेट स्रोत प्लगइन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:migrate:source [options]
gpms
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--plugin-id | प्लगिन आयडी
--table | क्वेरीसाठी टेबल.
--alias | सारणीचा सारांश म्हणून लघु उपनाव.
--group-by | फील्ड द्वारे गट परिणाम.
--fields | निर्यात करण्यासाठी फील्ड.

## उदाहरणे
* मॉड्यूलचे नाव, वर्ग, त्याचे प्लगिन आयडी, टेबल आणि तिचे उपनाव दर्शविणारे स्थानांतरण स्रोत प्लगइन उत्पन्न करा.
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="PluginClassName"  \
  --plugin-id="plugin_class_name"  \
  --table="DefaultTableName"  \
  --alias="D"
```
* मॉड्यूलचे नाव, वर्ग, त्याचे प्लगिन आयडी, टेबल, तिचे उपनाव आणि क्षेत्र निर्दिष्ट करणारे विशिष्ट वापरकर्त्यांसाठी मायग्रेशन स्त्रोत प्लगइन उत्पन्न करा.
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="DefaultPluginClass"  \
  --plugin-id="default_plugin_class"  \
  --table="users"  \
  --alias="u"  \
  --fields='"id":"id", "description":"the user id"'  \
  --fields='"id":"username", "description":"the username"'  \
  --fields='"id":"password", "description":"the user password"'  \
  --fields='"id":"email", "description":"the user email"'
```
