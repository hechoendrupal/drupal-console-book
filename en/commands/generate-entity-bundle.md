# generate:entity:bundle
Generate a new content type (node / entity bundle)

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:entity:bundle [options]
$ geb
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--bundle-name | The content type's machine name
--bundle-title | The content type's human-readable name

## commands.generate.doc.gitbook.messages.examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
