# generate:update
Generate an implementation of hook_update_N()

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:update [options]
$ gu
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--update-n | Update Number

## commands.generate.doc.gitbook.messages.examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
