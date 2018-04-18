# generate:plugin:rest:resource
生成 REST资源插件

**使用方法:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 插件REST资源类
--plugin-id | 插件REST资源id
--plugin-label | 插件REST资源标签
--plugin-url | 插件REST资源URL链接
--plugin-states | 插件REST资源状态

## 例子
* Generate a rest resource plugin using GET specifying the module name, the class, the plugin id, its label, the target url and the request type
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
