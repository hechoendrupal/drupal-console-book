# generate:plugin:imageformatter
Képformázó bővítmény létrehozása.

**Usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítményosztály neve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója

## Examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
