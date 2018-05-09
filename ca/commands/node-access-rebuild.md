# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**Ús:**
```
drupal node:access:rebuild [options]
nar
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--batch | Process in batch mode.

## Exemples
* Rebuild node access permissions
```
drupal node:access:rebuild --batch
```
