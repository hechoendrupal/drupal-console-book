# generate:post:update
Génère une implémentation de hook_post_update_NAME()

**Usage:**
```
drupal generate:post:update [options]
gpu
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--post-update-name | Nom du post update

## Examples
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
