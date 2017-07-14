# generate:plugin:condition
Hasilkan kondisi plugin.

**Usage:**
```
drupal generate:plugin:condition [options]
gpco
gpc
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Nama kelas kondisi plugin
--label | Label kondisi plugin
--plugin-id | ID kondisi plugin
--context-definition-id | ID definisi konteks
--context-definition-label | label definisi konteks
--context-definition-required | Definisi konteks diperlukan (TRUE/FALSE)

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
