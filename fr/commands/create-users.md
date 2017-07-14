# create:users
Génère des utilisateurs factices pour votre application Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Nombre d'utilisateurs à créer
--password | Mot de passe associé aux utilisateurs créés
--time-range | De combien de temps au maximum doivent dater les comptes utilisateurs générées ?

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | Les rôle(s) à utiliser pour la création d'utilisateurs

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
