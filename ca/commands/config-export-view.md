# config:export:view
Exportar una vista amb el format YAML en un mòdul per reutilitzar-lo en un altre lloc web.

**Ús:**
```
drupal config:export:view [arguments] [options]
cev
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--optional-config | Exportar vista com a configuració YAML opcional en el teu mòdul
--include-module-dependencies | Incloure les dependències del mòdul en un fitxer YAML

## Arguments disponibles
Argument | Detalls
---------|-------------
view-id | Identificador de la vista

## Exemples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
