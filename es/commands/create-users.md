# create:users
Crea usuarios de prueba para tu Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Cuántos usuarios le gustaría crear
--password | Contraseña de los usuarios creados
--time-range | Cuanta antelación debe tener la fecha de creación de los usuarios

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | Role(s) que serán usados en la creación de usuarios

## application.gitbook.messages.examples
* Provide the user role.
```
drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
