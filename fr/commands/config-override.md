# config:override
Surcharge la valeur d'une configuration dans la configuration active.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Nom de la configuration
key | Clé
value | Valeur

## application.gitbook.messages.examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
