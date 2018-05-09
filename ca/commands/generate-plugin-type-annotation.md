# generate:plugin:type:annotation
Generar un tipus de connector amb descobriment d'anotació

**Ús:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del conenctor
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Etiqueta del connector

## Exemples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
