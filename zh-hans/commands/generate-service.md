# generate:service
生成服务

**使用方法:**
```
drupal generate:service [options]
gs
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--name | 服务名
--class | 类名
--interface | 界面
--interface-name | Interface name
--services | 从容器加载服务。
--path-service | Path

## 例子
* Generate a services without interface specifying the module name, the service name, the class and its path
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --path-service="/modules/custom/modulename/src/"
```
* Generate a services with interface specifying the module name, the service name, the class, the interface name and its path
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --interface  \
  --interface-name="InterfaceName"  \
  --path-service="/modules/custom/modulename/src/"
```
