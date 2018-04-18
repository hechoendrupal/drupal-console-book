# generate:event:subscriber
生成事件订阅者

**使用方法:**
```
drupal generate:event:subscriber [options]
ges
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--name | Service name
--class | Class name
--events | 从容器中加载事件
--services | 从容器加载服务。

## 例子
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
