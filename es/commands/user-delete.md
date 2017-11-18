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
--user | Nombre de usuario o ID a eliminar
--roles | Roles asociados a los usuarios que serán eliminados

## Ejemplos
* Eliminar un usuario especificando el ID y el rol de usuario
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Eliminar un usuario especificando su ID
```
drupal user:delete  \
  --user-id="3"
```
* Eliminar usuarios con el rol "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
