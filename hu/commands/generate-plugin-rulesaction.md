# generate:plugin:rulesaction
Szabályművelet bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítményosztály neve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója
--type | Művelet típusa (felhasználó vagy tartalom)
--category | Bővítmény kategóriája
--context | Bővítmény kontextusa

## Examples
* Generate a user rule action plugin specifying the module name, the class, its label, the plugin id, the type, the category and its context
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="user"  \
  --category="default_action"  \
  --context="default_action"
```
* Generate a node rule action plugin specifying the module name, the class, its label, the plugin id, the type, the category and its context
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="node"  \
  --category="default_action" \
  --context="default_action"
```
