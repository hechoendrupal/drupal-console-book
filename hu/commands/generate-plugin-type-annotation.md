# generate:plugin:type:annotation
Bővítménytípus létrehozása magyarázatészleléssel

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítménytípus osztályneve
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Bővítménytípus felirata

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
