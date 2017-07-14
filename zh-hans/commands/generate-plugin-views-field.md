# generate:plugin:views:field
生成一个定制的插件视窗域.

**Usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 视窗插件域类名
--title | 视窗插件域标题
--description | 视窗插件域介绍

## Examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
