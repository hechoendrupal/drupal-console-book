# create:users
Crea usuarios de prueba para tu Drupal 8.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | Cuántos usuarios le gustaría crear
--password | Contraseña de los usuarios creados
--time-range | Cuanta antelación debe tener la fecha de creación de los usuarios

## Available arguments
Argument | Details
---------|-------------
roles | Role(s) que serán usados en la creación de usuarios

## Examples
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
