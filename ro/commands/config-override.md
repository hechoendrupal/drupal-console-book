# config:override
Suprascrie valoarea de configurare în configurarea activă.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Configuration name
key | Cheie
value | Valoare

## application.gitbook.messages.examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
