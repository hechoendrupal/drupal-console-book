# generate:plugin:type:yaml
Generar un tipus de connector amb descobriment de YAML

**Ús:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Nom de classe del tipus de connector
--plugin-name | Nom màquina de la classe del tipus de connector
--plugin-file-name | Nom del fitxer del connector

## Exemples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
