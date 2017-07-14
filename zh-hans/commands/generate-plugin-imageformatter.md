# generate:plugin:imageformatter
生成图像显示插件.

**Usage:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 插件类名
--label | 插件标签
--plugin-id | 插件id

## Examples
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
