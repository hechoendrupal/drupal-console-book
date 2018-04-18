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
operation | Add or remove
user | The affected user (only one)
role | Roles to add or remove. Please provide the machine name (only one)

## Examples
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
