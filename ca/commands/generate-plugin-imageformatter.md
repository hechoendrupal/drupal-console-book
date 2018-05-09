# generate:plugin:imageformatter
Generar un connector formatador de camp.

**Ús:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del connector
--label | Etiqueta del connector
--plugin-id | Identificador del connector

## Exemples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
