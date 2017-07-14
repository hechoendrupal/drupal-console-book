# debug:config
List configuration objects names and single configuration object.

**Usage:**
```
drupal debug:config [arguments]
dc
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration object name, for example "system.site".

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
