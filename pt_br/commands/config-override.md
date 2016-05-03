# config:override
Sobrescrever valor de configuração ativa.

**Uso:**
```
$ drupal config:override [arguments]
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
name | commands.config.override.arguments.name
key | Chave
value | Valor

## Exemplos
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
