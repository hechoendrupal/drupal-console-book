# config:override
Suprascrie valoarea de configurare în configurarea activă.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration name
key | Cheie
value | Valoare

## Examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
