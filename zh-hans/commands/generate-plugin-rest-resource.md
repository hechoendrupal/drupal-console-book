# generate:plugin:rest:resource
生成 REST资源插件

**Usage:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 插件REST资源类
--name | commands.generate.service.options.name
--plugin-id | 插件REST资源id
--plugin-label | 插件REST资源标签
--plugin-url | 插件REST资源URL链接
--plugin-states | 插件REST资源状态

## Examples
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
