# debug:plugin
Mostrar todos los tipos de plugin, instancias de plugin de un tipo específico, o la definición para un plugin específico.

**Usage:**
```
drupal debug:plugin [arguments]
dpl
```

## Available arguments
Argument | Details
---------|-------------
type | Tipo de plugin
id | ID del plugin

## Examples
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
