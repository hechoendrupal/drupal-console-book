# generate:plugin:imageeffect
Tạo plugin hiệu ứng hình ảnh

**Usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp plugin
--label | Nhãn plugin
--plugin-id | Plugin id
--description | Mô tả plugin

## Examples
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
