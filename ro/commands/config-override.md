# config:override
Suprascrie valoarea de configurare în configurarea activă.

**Folosire:**
```
$ drupal config:override [arguments]
```

## Argumente disponibile
Argument | Detalii
---------|-------------
config-name | Numele configurării.
key | Cheie
value | Valoare

## Exemple
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
