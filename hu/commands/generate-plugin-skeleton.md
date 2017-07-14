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
--module | A modul neve.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | Bővítmény osztályneve
--services | Szolgáltatások betöltése a tárolóból.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
