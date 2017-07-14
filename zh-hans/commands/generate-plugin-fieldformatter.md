# generate:plugin:fieldformatter
生成字段格式化器插件

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 插件类名
--label | 插件标签
--plugin-id | 插件 ID
--field-type | 字段类型，能与该插件一起使用的字段类型

## Examples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
