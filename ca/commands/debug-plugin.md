# debug:plugin
Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.

**Ús:**
```
drupal debug:plugin [arguments]
dpl
```

## Arguments disponibles
Argument | Detalls
---------|-------------
type | Plugin type
id | Plugin ID

## Exemples
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
