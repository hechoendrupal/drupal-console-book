# config:override
Sobrescrever valor de configuração ativa.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Configuration name
key | Chave
value | Valor

## application.gitbook.messages.examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
