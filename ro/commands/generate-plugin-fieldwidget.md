# generate:plugin:fieldwidget
Generează extensia de widget pentru câmp.

**Usage:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pentru extensie
--label | Eticheta extensiei
--plugin-id | ID-ul extensiei
--field-type | Tipul câmpului cu, care extensia poate fi folosită

## Examples
* Generate a text type field widget plugin specifying the module name, the class, its label, the plugin id and the field type
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
