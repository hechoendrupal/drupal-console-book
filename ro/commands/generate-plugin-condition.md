# generate:plugin:condition
Generează o condiție pentru extensie.

**Usage:**
```
drupal generate:plugin:condition [options]
gpco
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pentru condiția extensiei
--label | Eticheta pentru condiția extensiei
--plugin-id | ID-ul condiției extensiei
--context-definition-id | ID-ul definirii contextului
--context-definition-label | Eticheta definirii contextului
--context-definition-required | Definirea contextului este obligatorie (ADEVĂRAT/FALS)

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
