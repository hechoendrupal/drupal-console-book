# debug:module
Mostrar els mòduls disponibles per l'aplicació

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | Estat del mòdul [habilitat|deshabilitat]
--type | Tipus de mòdul [core|no-core]

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
