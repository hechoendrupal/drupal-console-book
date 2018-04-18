# generate:plugin:condition
प्लगिन नियम उत्पन्न करें।

**Usage:**
```
drupal generate:plugin:condition [options]
gpco
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन नियम क्लास नाम
--label | प्लगइन नियम उप-शीर्षक
--plugin-id | प्लगइन नियम id
--context-definition-id | प्रसंग परिभाषा id
--context-definition-label | प्रसंग परिभाषा उप-शीर्षक
--context-definition-required | प्रसंग परिभाषा आवश्यक है (सही/गलत)

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
