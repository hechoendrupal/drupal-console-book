# user:delete
Eliminar usuaris de l'aplicació

**Ús:**
```
drupal user:delete [options]
ud
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--user | User name/id to be deleted
--roles | Rols vinculats als usuaris a eliminar

## Exemples
* Delete user specifying the id and the user role
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Delete user specifying its id
```
drupal user:delete  \
  --user-id="3"
```
* Delete users with the role "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
