# generate:plugin:imageeffect
Génère un plugin d'effet d'image

**Usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Nom de la classe du plugin
--label | Label du plugin
--plugin-id | Id du plugin
--description | Description du plugin

## Examples
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
