# user:delete
Delete users for the application

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal user:delete [options]
$ ud
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--user-id | User id to be deleted
--roles | Roles associated to users to be deleted

## commands.generate.doc.gitbook.messages.examples
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
