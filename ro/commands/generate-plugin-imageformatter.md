# generate:plugin:imageformatter
Generează un plugin de formatare a imaginii.

**Usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pluginului
--label | Eticheta pluginului
--plugin-id | ID-ul pluginului

## Examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
