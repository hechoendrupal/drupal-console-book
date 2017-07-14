# generate:plugin:ckeditorbutton
Génère un plugin de bouton CKEditor.

**Usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Nom de la classe du plugin
--label | Label du plugin
--plugin-id | ID du plugin. NOTE: Correspond au nom du plugin CKEditor. Il s'agit du premier argument de la fonction CKEDITOR.plugins.add() dans le fichier plugin.js.
--button-name | Nom du bouton. NOTE: Correspond au nom du bouton de CKEditor. Il s'agit du premier argument de la fonction editor.ui.addButton() ou de la fonction editor.ui.addRichCombo() dans le fichier plugin.js.
--button-icon-path | Chemin de l'icône du bouton. Il s'agit du chemin vers l'icône/image du bouton.

## Examples
* Generate CKEditor button specifying the module name, the class, the label, its id, the button name and the icon path
```
drupal generate:plugin:ckeditorbutton  \
  --module="modulename"  \
  --class="DefaultCKEditorButton"  \
  --label="Default ckeditor button"  \
  --plugin-id="default ckeditor button"  \
  --button-name="Default ckeditor button"  \
  --button-icon-path="modules/custom/modulename/js/plugins/default ckeditor button/images/icon.png"
```
