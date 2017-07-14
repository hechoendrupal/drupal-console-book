# generate:plugin:fieldtype
Mezőtípus bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítmény osztályneve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója
--description | Bővítmény leírása
--default-widget | A bővítmény alapértelmezett mező felületi eleme
--default-formatter | A bővítmény alapértelmezett mezőformázója

## Examples
* Generate a field type plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"
```
* Generate a field type plugin with a default widget and formatter specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"  \
  --default-widget="DefaultWidget"  \
  --default-formatter="DefaultFormatter"
```
