# debug:module
Mostrar els mòduls disponibles per l'aplicació

**Ús:**
```
drupal debug:module [arguments] [options]
dm
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--status | Estat del mòdul [habilitat|deshabilitat]
--type | Tipus de mòdul [core|no-core]

## Arguments disponibles
Argument | Detalls
---------|-------------
module | Module name

## Exemples
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
