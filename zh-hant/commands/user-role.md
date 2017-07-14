# user:role
指派或移除使用者所屬角色

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
