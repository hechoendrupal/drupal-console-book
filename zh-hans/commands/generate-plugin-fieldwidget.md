# generate:plugin:fieldwidget
生成字段 Widget 插件

**Usage:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 插件类名
--label | 插件标签
--plugin-id | 插件 ID
--field-type | 字段类型，可以和该插件一起使用的字段类型

## Examples
* Generate a text type field widget plugin specifying the module name, the class, its label, the plugin id and the field type
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
