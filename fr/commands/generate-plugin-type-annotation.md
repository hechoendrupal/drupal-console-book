# generate:plugin:type:annotation
Génère un type de plugin avec des annotations (mécanisme de découverte)

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Nom de la classe du type de plugin
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Label du type de plugin

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
