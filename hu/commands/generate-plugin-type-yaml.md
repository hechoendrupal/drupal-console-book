# generate:plugin:type:yaml
Bővítménytípus létrehozása YAML-észleléssel

**Usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítménytípus osztályneve
--plugin-name | Bővítménytípus programok által használt neve
--plugin-file-name | Bővítmény fájlneve

## Examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
