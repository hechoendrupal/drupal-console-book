# user:delete
Delete users for the application

**application.gitbook.messages.usage:**
```
drupal user:delete [options]
ud
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--user-id | User id to be deleted
--roles | Roles associated to users to be deleted

## application.gitbook.messages.examples
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
