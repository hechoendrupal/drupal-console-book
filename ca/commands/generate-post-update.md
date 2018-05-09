# generate:post:update
Generate an implementation of hook_post_update_NAME()

**Ús:**
```
drupal generate:post:update [options]
gpu
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--post-update-name | Post Update Name

## Exemples
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
