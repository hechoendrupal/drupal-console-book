# generate:plugin:type:annotation
生成一个有识别注解能力的插件类别

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 插件类别类名
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | 插件类别标签

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
