# generate:entity:bundle
Génère un nouveau type de contenu (nœud / bundle d'entité)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--bundle-name | Le nom machine du type de contenu
--bundle-title | Le nom lisible par les utilisateurs du type de contenu

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
