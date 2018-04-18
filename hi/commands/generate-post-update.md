# generate:post:update
Generate an implementation of hook_post_update_NAME()

**Usage:**
```
drupal generate:post:update [options]
gpu
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--post-update-name | Post Update Name

## Examples
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
