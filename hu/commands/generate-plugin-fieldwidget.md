# generate:plugin:fieldwidget
Mező felületi elem bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítmény osztályneve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója
--field-type | A mezőtípus, amivel a bővítmény használható

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
