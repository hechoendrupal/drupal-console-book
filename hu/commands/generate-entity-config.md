# generate:entity:config
Új konfigurációs entitás létrehozása

**Usage:**
```
drupal generate:entity:config [options]
gec
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--entity-class | A konfigurációs entitás osztálya
--entity-name | A konfigurációs entitás neve
--base-path | A konfigurációs entitások útvonalainak alapútvonala
--label | A felirat
--bundle-of | A tartalomentitások mezőkötegeként funkcionál

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
