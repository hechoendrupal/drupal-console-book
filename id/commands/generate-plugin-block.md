# generate:plugin:block
Hasilkan blok plugin

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Nama kelas plugin
--label | Label plugin
--plugin-id | ID plugin
--theme-region | Wilayah tema untuk meletakkan blok plugin
--inputs | Buat input dalam formulir.
--services | Memuat servis dari kontainer.

## Examples
* Generate a plugin block in the header region with an input field specifying the module name, the class, the label, its id, the region and the input
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
