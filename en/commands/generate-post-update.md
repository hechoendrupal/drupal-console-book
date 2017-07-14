# generate:post:update
commands.generate.post:update.description

**application.gitbook.messages.usage:**
```
drupal generate:post:update [options]
gpu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--post-update-name | Post Update Name

## application.gitbook.messages.examples
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
