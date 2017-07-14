# generate:plugin:fieldformatter
Tạo một formatter plugin.

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp plugin
--label | Nhãn plugin
--plugin-id | Plugin id
--field-type | Loại field mà plugin có thể được sử dụng với

## Examples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
