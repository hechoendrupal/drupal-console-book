# user:delete
Felhasználók törlése

**Usage:**
```
drupal user:delete [options]
ud
```

## Available options
Option | Details
-------|-------------
--user-id | Törölni kívánt felhasználói azonosító
--roles | A törölni kívánt felhasználókkal társított szerepkörök

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
