# generate:entity:config
Generează o entitate de configurare nouă

**Usage:**
```
drupal generate:entity:config [options]
gec
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--entity-class | Clasa entității de configurare
--entity-name | Numele entității de configurare
--base-path | The base-path for the config entity routes
--label | Eticheta
--bundle-of | Acts as bundle for content entities

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
