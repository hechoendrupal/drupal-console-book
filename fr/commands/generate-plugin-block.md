# generate:plugin:block
Génère un plugin de bloc

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Nom de la classe plugin
--label | Label du plugin
--plugin-id | Id du plugin
--theme-region | Région du thème où placer le plugin de bloc
--inputs | Créer des entrées dans un formulaire.
--services | Charger des services depuis le conteneur.

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
