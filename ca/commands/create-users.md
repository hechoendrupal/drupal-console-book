# create:users
Crear usuaris 'dummy' per l'aplicació Drupal 8.

**Ús:**
```
drupal create:users [arguments] [options]
cru
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--limit | Quants usuaris voldrieu crear
--password | La contrasenya que s'utilitzarà per els usuaris creats
--time-range | Quant de temps enrere ha de ser la data dels usuaris

## Arguments disponibles
Argument | Detalls
---------|-------------
roles | Rol(s) utilitzats en la creació d'usuaris

## Exemples
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
