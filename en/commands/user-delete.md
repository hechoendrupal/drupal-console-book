# user:delete
Delete users from the application

**Usage:**
```
drupal user:delete [options]
ud
```

## Available options
Option | Details
-------|-------------
--user | User name/id to be deleted
--roles | Users with the listed roles to be deleted

## Examples
* Delete user with the id number 2
```
drupal user:delete  \
  --user="2"
```
* Delete user with the username "jmolivas"
```
drupal user:delete  \
  --user="jmolivas"
```
* Delete users with the role "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
