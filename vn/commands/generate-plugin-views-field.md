# generate:plugin:views:field
Tạo một tùy chỉnh plugin view field.

**Usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp views plugin field
--title | Tiêu đề views plugin field
--description | Mô tả views plugin field

## Examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
