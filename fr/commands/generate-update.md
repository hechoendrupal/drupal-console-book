# generate:update
Génère une implémentation de hook_update_N()

**Usage:**
```
drupal generate:update [options]
gu
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--update-n | Numéro de mise à jour

## Examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
