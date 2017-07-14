# config:override
Surcharge la valeur d'une configuration dans la configuration active.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Nom de la configuration
key | Clé
value | Valeur

## Examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
