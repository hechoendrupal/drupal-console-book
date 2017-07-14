# generate:plugin:skeleton
为没有特定生成器的生成一个基本插件的实现

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--plugin-id | commands.generate.plugin.options.plugin-id
--class | 插件类名
--services | 从容器中导入服务

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
