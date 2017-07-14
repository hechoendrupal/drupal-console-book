# generate:plugin:imageformatter
Generate image formatter plugin.

**Usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id

## Examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
