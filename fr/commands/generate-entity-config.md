# generate:entity:config
Génère une nouvelle entité de configuration

**Usage:**
```
drupal generate:entity:config [options]
gec
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--entity-class | La classe de l'entité de configuration
--entity-name | Le nom de l'entité de configuration
--base-path | Le chemin de base des routes de l'entité de configuration
--label | Le label
--bundle-of | Intervient en tant que bundle d'entités de contenu

## Examples
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
