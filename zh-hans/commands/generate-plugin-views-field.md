# generate:plugin:views:field
生成一个定制的插件视窗域.

**使用方法:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 视窗插件域类名
--title | 视窗插件域标题
--description | 视窗插件域介绍

## 例子
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
