# generate:plugin:field
Tạo field type, widget và formatter plugins.

**Usage:**
```
$ drupal generate:plugin:field [options]
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--module | Tên module.
--type-class | Tên lớp field type plugin
--type-label | Nhãn field type plugin
--type-plugin-id | Field type plugin id
--type-description | commands.generate.plugin.field.options.type-type-description
--formatter-class | commands.generate.plugin.field.options.class
--formatter-label | Nhãn field formatter plugin
--formatter-plugin-id | Field formatter plugin id
--widget-class | Tên lớp field formatter plugin
--widget-label | Nhãn field widget plugin
--widget-plugin-id | Field widget plugin id
--field-type | Field type mà formatter và widget plugin có thể được sử dụng với
--default-widget | Field widget mặc định của field type plugin
--default-formatter | Field formatter mặc định của field type plugin
