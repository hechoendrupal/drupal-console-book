# create:users
Crea usuarios de prueba para tu Drupal 8.

**Uso:**
```
drupal create:users [arguments] [options]
cru
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--limit | Cuántos usuarios le gustaría crear
--password | Contraseña de los usuarios creados
--time-range | Cuanta antelación debe tener la fecha de creación de los usuarios

## Argumentos disponibles
Argumento | Detalles
---------|-------------
roles | Role(s) que serán usados en la creación de usuarios

## Ejemplos
* Facilitar el rol de usuario.
```
drupal create:users role
```
* Facilitar el número de usuarios a crear, la contraseña y el rango de tiempo.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
