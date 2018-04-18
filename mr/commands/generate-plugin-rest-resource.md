# generate:plugin:rest:resource
प्लगइन उर्वरित संसाधन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन रेस संसाधन वर्ग.
--plugin-id | प्लगइन प्रवासी संसाधन आयडी
--plugin-label | प्लगइन उर्वरीत संसाधन लेबल.
--plugin-url | प्लगइन उर्वरित संसाधन URL
--plugin-states | प्लगइन रीस्ट रिसोर्स स्टेटस.

## उदाहरणे
* मॉड्यूल नाव, वर्ग, प्लगिन आयडी, त्याचे लेबल, लक्ष्य url आणि विनंती प्रकार निर्दिष्ट करून उर्वरित संसाधन प्लगइन उत्पन्न करा.
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
