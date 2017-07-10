# create:users
Create dummy users for your Drupal 8 application.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:users [arguments] [options]
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | How many users would you like to create
--password | Password to be set to users created
--time-range | How far back in time should the users be dated

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
roles | Role(s) to be used in user creation

## commands.generate.doc.gitbook.messages.examples
* Provide the user role.
```
$ drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
$ drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"

```
