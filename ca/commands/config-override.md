# config:override
Sobreescriure el valor de la configuració activa.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration name
key | Clau
value | Valor

## Examples
* Definir el valor de "flood" del mòdul Contact a 10.
```
drupal config:override contact.settings flood.limit 10
```
