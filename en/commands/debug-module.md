# debug:module
Displays current modules available for application

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | Module status [installed|uninstalled]
--type | Module type [core|no-core]

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
