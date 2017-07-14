# debug:module
Afişează Modulele curente pentru aplicaţie

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | Starea Modulului [activat|dezactivat]
--type | Tipul Modulului [core|no-core]

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
