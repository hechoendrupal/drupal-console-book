# generate:plugin:imageformatter
Generate image formatter plugin.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id

## application.gitbook.messages.examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
