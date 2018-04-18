# generate:plugin:type:yaml
Yaml शोधसह एक प्लगिन प्रकार उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन प्रकार वर्ग नाव.
--plugin-name | प्लगिन प्रकार मशीनचे नाव.
--plugin-file-name | प्लगइन फाइल नाव.

## उदाहरणे
* मॉडेल नाव, वर्ग नाव, प्लगिन नाव आणि प्लगिन फाइल नाव निर्दिष्ट केलेल्या Yaml डिस्कवरीसह एक प्लगिन उत्पन्न करा.
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
