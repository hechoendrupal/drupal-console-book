# generate:plugin:skeleton
Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | O nome do módulo.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | Nome da classe do plugin
--services | Carrega serviços do container.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
