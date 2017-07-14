# user:password:reset
Réinitialise le mot de passe pour un utilisateur spécifique.

**Usage:**
```
drupal user:password:reset [arguments]
upr
uspr
```

## Available arguments
Argument | Details
---------|-------------
user | ID de l'utilisateur
password | Mot de passe au format texte

## Examples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
