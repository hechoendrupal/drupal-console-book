# generate:plugin:fieldwidget
Hasilkan plugin untuk field widget.

**Usage:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Nama kelas plugin
--label | Label plugin
--plugin-id | ID plugin
--field-type | Tipe field yang dapat digunakan

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
