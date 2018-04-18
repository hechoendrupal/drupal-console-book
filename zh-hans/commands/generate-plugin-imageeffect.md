# generate:plugin:imageeffect
生成图像效果插件

**使用方法:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 插件类名
--label | 插件标签
--plugin-id | 插件 ID
--description | 插件描述

## 例子
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
