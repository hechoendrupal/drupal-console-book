# generate:plugin:type:yaml
生成一个有识别Yaml能力的插件类别

**使用方法:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 插件类型类名
--plugin-name | 插件类别内部机读名称
--plugin-file-name | 插件文件名

## 例子
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
