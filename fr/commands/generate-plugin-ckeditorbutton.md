# generate:plugin:ckeditorbutton
Génère un plugin de bouton CKEditor.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Le nom du module.
--class | Nom de la classe du plugin
--label | Label du plugin
--plugin-id | ID du plugin. NOTE: Correspond au nom du plugin CKEditor. Il s'agit du premier argument de la fonction CKEDITOR.plugins.add() dans le fichier plugin.js.
--button-name | Nom du bouton. NOTE: Correspond au nom du bouton de CKEditor. Il s'agit du premier argument de la fonction editor.ui.addButton() ou de la fonction editor.ui.addRichCombo() dans le fichier plugin.js.
--button-icon-path | Chemin de l'icône du bouton. Il s'agit du chemin vers l'icône/image du bouton.
