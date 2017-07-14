# generate:plugin:type:annotation
Generează un tip de plugin cu descoperire de adnotaţii

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei tipului de plugin.
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Eticheta tipului de plugin.

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
