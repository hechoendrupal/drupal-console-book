# generate:plugin:condition
प्लगिन स्थिती उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:condition [options]
gpco
gpc
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगिन स्थिती वर्ग नाव.
--label | प्लगिन स्थिती लेबल.
--plugin-id | प्लगिन स्थिती आयडी.
--context-definition-id | संदर्भ व्याख्या आयडी.
--context-definition-label | संदर्भ व्याख्या लेबल.
--context-definition-required | संदर्भ व्याख्या आवश्यक आहे (सत्य / चूक)

## Examples
* Generate a plugin condition for a node entity type specifying the module name, the class, the label, its id and the context definition
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
* Generate a plugin condition for language specifying the module name, the class, the label, its id and the context definition
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
* Generate a plugin condition for role configuration specifying the module name, the class, the label, its id and the context definition
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
