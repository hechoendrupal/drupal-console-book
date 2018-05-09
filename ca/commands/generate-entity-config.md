# generate:entity:config
Generar una nova entitat de continguts

**Ús:**
```
drupal generate:entity:config [options]
gec
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--entity-class | Classe de l'entitat de continguts
--entity-name | Nom de l'entitat de continguts
--base-path | El camí base per la configuració de rutes d'entitats
--label | Etiqueta
--bundle-of | Actua com a 'bundle' per l'entitat de continguts

## Exemples
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
