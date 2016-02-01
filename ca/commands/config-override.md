# config:override
El comandament **config:override** executa Sobreescriure el valor de la configuració activa.

**Ús:**
```
$ drupal config:override [arguments] 
```

## Arguments disponibles
Argument | Detalls
---------|-------------
config-name | Nom de la configuració.
key | Clau
value | Valor

## Exemples
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
