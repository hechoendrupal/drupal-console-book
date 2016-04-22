# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**प्रयोग:**
```
$ drupal node:access:rebuild [options]
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--batch | Process in batch mode.

## उदाहरण
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
