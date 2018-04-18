# config:override
Sobrescrever valor de configuração ativa.

**Utilização:**
```
drupal config:override [arguments]
co
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
name | Configuration name
key | Chave
value | Valor

## Exemplos
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
