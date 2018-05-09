# config:override
Sobreescriure el valor de la configuració activa.

**Ús:**
```
drupal config:override [arguments]
co
```

## Arguments disponibles
Argument | Detalls
---------|-------------
name | Configuration name
key | Clau
value | Valor

## Exemples
* Definir el valor de "flood" del mòdul Contact a 10.
```
drupal config:override contact.settings flood.limit 10
```
