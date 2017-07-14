# generate:plugin:rulesaction
Generate a plugin rule action

**Usage:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--type | Action Type (user or node)
--category | Plugin category
--context | Plugin context

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
