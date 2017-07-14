# generate:plugin:fieldformatter
Hasilkan plugin untuk pemformat field.

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Nama kelas plugin
--label | Label plugin
--plugin-id | ID plugin
--field-type | Tipe field yang dapat digunakan oleh plugin

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
