# generate:post:update
Generate an implementation of hook_post_update_NAME()

**Utilização:**
```
drupal generate:post:update [options]
gpu
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--post-update-name | Post Update Name

## Exemplos
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
