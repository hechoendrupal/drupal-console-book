# generate:plugin:imageeffect
Generează un plugin pentru efecte de imagini.

**Usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pluginului
--label | Eticheta pluginului
--plugin-id | Id-ul pluginului
--description | Descrierea pluginului

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
