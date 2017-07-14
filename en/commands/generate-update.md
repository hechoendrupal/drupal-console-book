# generate:update
Generate an implementation of hook_update_N()

**application.gitbook.messages.usage:**
```
drupal generate:update [options]
gu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--update-n | Update Number

## application.gitbook.messages.examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
