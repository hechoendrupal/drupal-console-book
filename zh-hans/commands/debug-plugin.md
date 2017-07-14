# debug:plugin
显示所有插件类型,指定类型的插件实例,或指定插件的定义

**Usage:**
```
drupal debug:plugin [arguments]
dpl
```

## Available arguments
Argument | Details
---------|-------------
type | 插件类型
id | 插件 ID

## Examples
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
