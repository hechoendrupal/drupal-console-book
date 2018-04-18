# generate:plugin:field
Tạo field type, widget và formatter plugins.

**Usage:**
```
drupal generate:plugin:field [options]
gpf
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--type-class | Tên lớp field type plugin
--type-label | Nhãn field type plugin
--type-plugin-id | Field type plugin id
--type-description | Mô tả field type plugin
--formatter-class | Tên lớp field formatter plugin
--formatter-label | Nhãn field formatter plugin
--formatter-plugin-id | Field formatter plugin id
--widget-class | Tên lớp field formatter plugin
--widget-label | Nhãn field widget plugin
--widget-plugin-id | Field widget plugin id
--field-type | Field type mà formatter và widget plugin có thể được sử dụng với
--default-widget | Field widget mặc định của field type plugin
--default-formatter | Field formatter mặc định của field type plugin

## Examples
* Generate field type, widget and formatter plugins specifying the module name, the type (class, label, plugin id and description), the formatter (class, label, plugin id) and the widget (class, label and plugin id)
```
drupal generate:plugin:field  \
  --module="modulename"  \
  --type-class="ExampleFieldType"  \
  --type-label="Example field type"  \
  --type-plugin-id="example_field_type"  \
  --type-description="My Field Type"  \
  --formatter-class="ExampleFormatterType"  \
  --formatter-label="Example formatter type"  \
  --formatter-plugin-id="example_formatter_type"  \
  --widget-class="ExampleWidgetType"  \
  --widget-label="Example widget type"  \
  --widget-plugin-id="example_widget_type"  \
  --field-type="example_field_type"  \
  --default-widget="example_widget_type"  \
  --default-formatter="example_formatter_type"
```
