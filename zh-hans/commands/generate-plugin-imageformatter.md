# generate:plugin:imageformatter
生成图像显示插件.

**使用方法:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 插件类名
--label | 插件标签
--plugin-id | 插件id

## 例子
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
