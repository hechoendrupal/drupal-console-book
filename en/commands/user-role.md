# user:role
Adds/removes a role for a given user

**Usage:**
```
drupal user:role [arguments]
ur
```

## Available arguments
Argument | Details
---------|-------------
operation | commands.user.role.operation
user | commands.user.role.user
role | commands.user.role.role

## Examples
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
