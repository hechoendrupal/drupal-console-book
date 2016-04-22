# config:export:view
Export 1 view trong YAML format inside 1 module được cung cấp để sử dụng lại trên các website khác.

**Usage:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--module | Tên module.
--optional-config | Export view như một lựa chọn YAML configuration trong module của bạn
--include-module-dependencies | Bao gồm module dependencies trong module info YAML file

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
view-id | View ID
