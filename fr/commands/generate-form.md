# generate:form
Génère un nouveau "%s"

**Usage:**
```
drupal generate:form [options]
gf
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Le nom de classe du formulaire
--form-id | l'ID du formulaire
--services | Charger des services depuis le conteneur.
--config-file | Add a config file
--inputs | Créer des entrées dans un formulaire.
--path | Entrez le chemin du formulaire
--menu-link-gen | Generate a menu link
--menu-link-title | A title for the menu link
--menu-parent | Menu parent
--menu-link-desc | A description for the menu link

## Examples
* Generate an empty form with config file specifying the module name, the class, a form id and the path
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --path="/modulename/form/default"
```
* Generate a form with 2 fields and a config file specifying the module name, the class, a form id, the inputs and the path
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --inputs='"name":"inputname", "type":"text_format", "label":"InputName", "options":"", "description":"Just a text input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --path="/modulename/form/default"
```
