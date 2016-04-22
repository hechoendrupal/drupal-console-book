# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**Usage:**
```
$ drupal node:access:rebuild [options]
```

## Available options
Option | Details
-------|-------------
--batch | Process in batch mode.

## Examples
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
