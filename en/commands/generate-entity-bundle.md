# generate:entity:bundle
Generate a new content type (node / entity bundle)

**application.gitbook.messages.usage:**
```
drupal generate:entity:bundle [options]
geb
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--bundle-name | The content type's machine name
--bundle-title | The content type's human-readable name

## application.gitbook.messages.examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
