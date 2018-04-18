# generate:entity:config
Tạo một config entity mới

**Usage:**
```
drupal generate:entity:config [options]
gec
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--entity-class | Lớp config entity
--entity-name | Tên config entity
--base-path | The base-path for the config entity routes
--label | Nhãn
--bundle-of | Các hành động bundle cho nội dung entities

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
