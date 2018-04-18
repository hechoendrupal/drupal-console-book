# user:delete
ユーザーを削除

**Usage:**
```
drupal user:delete [options]
ud
```

## Available options
Option | Details
-------|-------------
--user | User name/id to be deleted
--roles | 削除するユーザーに関連付けられたロール

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
* Delete users with the role "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
