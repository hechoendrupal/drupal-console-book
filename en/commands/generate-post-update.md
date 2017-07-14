# generate:post:update
commands.generate.post:update.description

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:post:update [options]
gpu
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--post-update-name | Post Update Name

## commands.generate.doc.gitbook.messages.examples
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
