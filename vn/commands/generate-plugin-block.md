# generate:plugin:block
Tạo một plugin block

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp plugin
--label | Nhãn plugin
--plugin-id | Plugin id
--theme-region | Theme region để render Plugin Block
--inputs | Tạo các đầu vào trong một form.
--services | Nạp các dịch vụ từ container.

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
