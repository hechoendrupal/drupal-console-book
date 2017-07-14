# generate:entity:config
Hasilkan entitas konfigurasi baru

**Usage:**
```
drupal generate:entity:config [options]
gec
gecg
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--entity-class | Kelas entitas konfigurasi.
--entity-name | Nama entitas konfigurasi
--base-path | Path dasar dari rute entitas konfigurasi
--label | Label
--bundle-of | Bertindak sebagai bundel dari entitas-entitas kontent

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
