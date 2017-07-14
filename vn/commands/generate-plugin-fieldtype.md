# generate:plugin:fieldtype
Tạo field type plugin.

**Usage:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp plugin
--label | Nhãn plugin
--plugin-id | Plugin id
--description | Mô tả plugin
--default-widget | Field widget mặc định của plugin này
--default-formatter | Field formatter mặc định của plugin này

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
