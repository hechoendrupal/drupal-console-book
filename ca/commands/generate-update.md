# generate:update
Generate an implementation of hook_update_N()

**Ús:**
```
drupal generate:update [options]
gu
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--update-n | Update Number

## Exemples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
