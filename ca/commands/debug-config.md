# debug:config
Mostrar la configuració actual

**Ús:**
```
drupal debug:config [arguments] [options]
dc
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--show-overridden | Show overridden configurations.

## Arguments disponibles
Argument | Detalls
---------|-------------
name | Nom de la configuració

## Exemples
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
