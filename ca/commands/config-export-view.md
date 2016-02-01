# config:export:view
El comandament **config:export:view** executa Exporta un vista amb el format YAML en un mòdul per reutilitzar-ho en un altre lloc web.

**Ús:**
```
$ drupal config:export:view [arguments] [options] 
$ cev  
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
view-id | ID de la vista
