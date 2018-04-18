# generate:plugin:condition
Feltételbővítmény létrehozása.

**Usage:**
```
drupal generate:plugin:condition [options]
gpco
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Feltételbővítmény osztályneve
--label | Feltételbővítmény felirata
--plugin-id | Feltételbővítmény azonosítója
--context-definition-id | Kontextusmeghatározás azonosítója
--context-definition-label | Kontextusmeghatározás felirata
--context-definition-required | A kontextusmeghatározás kötelező (TRUE/FALSE)

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
