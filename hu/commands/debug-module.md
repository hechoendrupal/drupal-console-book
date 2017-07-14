# debug:module
Az alkalmazáshoz elérhető aktuális modulok megjelenítése

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | Modul állapota [engedélyezett|tiltott]
--type | Modul típusa [alaprendszer|nem alaprendszer]

## Available arguments
Argument | Details
---------|-------------
module | Module name

## Examples
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
