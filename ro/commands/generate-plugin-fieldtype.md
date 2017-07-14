# generate:plugin:fieldtype
Generează extensia de tip câmp.

**Usage:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pentru extensie
--label | Eticheta extensiei
--plugin-id | ID-ul extensiei
--description | Descrierea extensiei
--default-widget | Valoarea implicită a acestei extensii pentru widgetul câmpului
--default-formatter | Valoarea implicită a acestei extensii pentru formatarea câmpului

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
