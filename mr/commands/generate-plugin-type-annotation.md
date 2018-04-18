# generate:plugin:type:annotation
भाष्येच्या शोधासह प्लगिन प्रकार उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन प्रकार वर्ग नाव
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | प्लगइन प्रकार लेबल.

## उदाहरणे
* मॉड्यूल नाव, वर्ग नाव, मशीनचे नाव आणि लेबल निर्दिष्ट करणारे भाष्यशोधसह प्लगइन उत्पन्न करा.
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
