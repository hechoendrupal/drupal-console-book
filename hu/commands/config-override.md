# config:override
The **config:override** command Beállítás felülírása.

**Usage:**
```
$ drupal config:override [arguments] 
```

## Available arguments
Argument | Details
---------|-------------
config-name | Beállítás neve.
key | Kulcs
value | Érték

## Examples
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
