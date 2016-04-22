# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**Használat:**
```
$ drupal node:access:rebuild [options]
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--batch | Process in batch mode.

## Példák
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
