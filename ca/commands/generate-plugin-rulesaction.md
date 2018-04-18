# generate:plugin:rulesaction
Generar un connector d'acció de regla

**Usage:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--class | Nom de la clase del connector
--label | Etiqueta del connector
--plugin-id | Identificador del connector
--type | Tipus d'acció (usuari o node)
--category | Categoría del connector
--context | Context del connector

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
