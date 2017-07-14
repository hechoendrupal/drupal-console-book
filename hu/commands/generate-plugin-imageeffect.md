# generate:plugin:imageeffect
Képhatás bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítmény osztályneve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója
--description | Bővítmény leírása

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
