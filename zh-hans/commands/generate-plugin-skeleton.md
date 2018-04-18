# generate:plugin:skeleton
为没有特定生成器的生成一个基本插件的实现

**使用方法:**
```
drupal generate:plugin:skeleton [options]
gps
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--plugin-id | 插件 Id.
--class | 插件类名
--services | 从容器加载服务。

## 例子
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
