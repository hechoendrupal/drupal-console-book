# generate:plugin:rulesaction
Genera un plugin de acción de rules

**Usage:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--type | Tipo de acción (usuario o nodo)
--category | Categoría del plugin
--context | Contexto del plugin

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
