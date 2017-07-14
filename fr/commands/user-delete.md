# user:delete
Supprime des utilisateurs de l'application

**Usage:**
```
drupal user:delete [options]
ud
```

## Available options
Option | Details
-------|-------------
--user-id | Id de l'utilisateur à supprimer
--roles | Rôles associés aux utilisateurs à supprimer

## Examples
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
