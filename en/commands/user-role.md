# user:role
Adds/removes a role for a given user

**application.gitbook.messages.usage:**
```
drupal user:role [arguments]
ur
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
operation | commands.user.role.operation
user | commands.user.role.user
role | commands.user.role.role

## application.gitbook.messages.examples
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
