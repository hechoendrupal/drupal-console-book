# generate:entity:bundle
Tạo một loại nội dung mới (node / entity bundle)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--bundle-name | Tên máy của loại nội dung
--bundle-title | Tên có thể đọc được của loại nội dung

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
