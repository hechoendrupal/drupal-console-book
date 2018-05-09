# server
Lance le serveur web PHP interne

**Usage:**
```
drupal server [arguments]
serve
rs
```

## Available arguments
Argument | Details
---------|-------------
address | Les valeurs adresse:port

## Examples
* Lancer en utilisant en argument la valeur d'adresse par défaut 127.0.0.1:8088
```
serveur drupal
```
* Passer en argument une adresse pour utiliser un numéro de port différent
```
serveur drupal 127.0.0.1:8089
```
* Lancement avec en argument les valeurs d'adresse par défaut, en utilisant l'option --root pour définir la racine Drupal
```
drupal --root=/var/www/drupal8.dev server
```
