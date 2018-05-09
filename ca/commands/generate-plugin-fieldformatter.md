# generate:plugin:fieldformatter
Generar un connector formatador de camp.

**Ús:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del connector
--label | Etiqueta del connector
--plugin-id | Identificador del connector
--field-type | Tipus de camp amb el que el connector es pot utilitzar

## Exemples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
