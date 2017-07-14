# generate:post:update
commands.generate.post:update.description

**Usage:**
```
drupal generate:post:update [options]
gpu
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--post-update-name | Post Update 名称

## Examples
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
