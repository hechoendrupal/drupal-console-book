# debug:config
Показывает текущую конфигурацию.

**Usage:**
```
drupal debug:config [arguments]
dc
```

## Available arguments
Argument | Details
---------|-------------
name | Имя конфигурации.

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
