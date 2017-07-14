# generate:form:alter
Tạo một implementation của hook_form_alter() hoặc hook_form_FORM_ID_alter

**Usage:**
```
drupal generate:form:alter [options]
gfa
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--form-id | Từ ID đến alter
--inputs | Tạo các đầu vào trong một form.

## Examples
* Generate a hook form alter for an empty form specifying the module name
```
drupal generate:form:alter  \
  --module="modulename"
```
* Generate a hook form alter with 2 fields specifying the module name and the inputs
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
