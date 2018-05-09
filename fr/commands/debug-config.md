# debug:config
Affiche la configuration actuelle.

**Usage:**
```
drupal debug:config [arguments] [options]
dc
```

## Available options
Option | Details
-------|-------------
--show-overridden | Show overridden configurations.

## Available arguments
Argument | Details
---------|-------------
name | Nom de la configuration.

## Examples
* List all configuration object names.
```
drupal config:debug
```
* Display system site configurations values.
```
drupal config:debug system.site
```
* List all system configuration names.
```
drupal config:debug | grep system
```
* List all configuration including overridden values.
```
drupal debug:config --show-overridden
```
