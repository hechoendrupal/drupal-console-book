# generate:plugin:field
生成字段类型、Widget和格式化器的插件

**使用方法:**
```
drupal generate:plugin:field [options]
gpf
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--type-class | 字段类型插件类名
--type-label | 字段类型插件标签
--type-plugin-id | 字段类型插件 ID
--type-description | 字段类型插件描述
--formatter-class | 字段格式化器插件类名
--formatter-label | 字段格式化器插件标签
--formatter-plugin-id | 字段格式化器插件 ID
--widget-class | 字段格式化器插件类名
--widget-label | 字段 Widget 插件标签
--widget-plugin-id | 字段 Widget 插件 ID
--field-type | 和字段格式化器插件和 Widget 插件一起使用的字段类型
--default-widget | 字段类型插件的默认字段 Widget
--default-formatter | 字段类型插件的默认字段格式化器

## 例子
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
