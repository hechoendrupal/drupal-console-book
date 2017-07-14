# generate:plugin:block
Generează un Plugin de tip bloc

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pluginului
--label | Eticheta pluginului
--plugin-id | ID-ul pluginului
--theme-region | Regiunea temei unde va fi randat Pluginul de tip bloc
--inputs | Creează intrări într-un formular.
--services | Încarcă serviciile din container.

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
