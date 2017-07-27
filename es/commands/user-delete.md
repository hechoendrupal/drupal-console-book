# user:delete
Eliminar usuarios del sitio

**Uso:**
```
drupal user:delete [options]
ud
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--user-id | Id de usuario que será eliminado
--roles | Roles asociados a los usuarios que serán eliminados

## Ejemplos
* Eliminar un usuario especificando el id y el rol de usuario
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Eliminar un usuario especificando su id
```
drupal user:delete  \
  --user-id="3"
```
