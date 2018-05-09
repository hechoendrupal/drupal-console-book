# create:users
Génère des utilisateurs factices pour votre application Drupal 8.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | Nombre d'utilisateurs à créer
--password | Mot de passe associé aux utilisateurs créés
--time-range | De combien de temps au maximum doivent dater les comptes utilisateurs générées ?

## Available arguments
Argument | Details
---------|-------------
roles | Les rôle(s) à utiliser pour la création d'utilisateurs

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
