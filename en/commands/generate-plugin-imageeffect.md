# generate:plugin:imageeffect
Generate image effect plugin.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--description | Plugin Description

## application.gitbook.messages.examples
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
