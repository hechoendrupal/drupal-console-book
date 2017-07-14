# generate:event:subscriber
生成事件订阅者

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--name | commands.generate.service.options.name
--class | 类名
--events | 从容器中导入事件
--services | 从容器中导入服务

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
