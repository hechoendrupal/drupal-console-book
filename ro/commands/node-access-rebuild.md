# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**Folosire:**
```
$ drupal node:access:rebuild [options]
```

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--batch | Process in batch mode.

## Exemple
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
