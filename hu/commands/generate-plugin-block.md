# generate:plugin:block
Blokk bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítmény osztályneve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója
--theme-region | Smink azon régiója, ahol a blokk bővítménynek meg kell jelennie
--inputs | Bemenetek létrehozása egy űrlapban.
--services | Szolgáltatások betöltése a tárolóból.

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
