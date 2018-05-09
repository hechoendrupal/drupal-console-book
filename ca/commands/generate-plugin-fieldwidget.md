# generate:plugin:fieldwidget
Generar connector de giny de camp.

**Ús:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
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
* Generate a text type field widget plugin specifying the module name, the class, its label, the plugin id and the field type
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
