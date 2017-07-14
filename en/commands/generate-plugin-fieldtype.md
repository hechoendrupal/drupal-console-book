# generate:plugin:fieldtype
Generate field type plugin.

**Usage:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--description | Plugin Description
--default-widget | Default field widget of this plugin
--default-formatter | Default field formatter of this plugin

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
