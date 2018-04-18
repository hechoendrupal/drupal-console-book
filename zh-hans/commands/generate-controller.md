# generate:controller
生成并注册新控制器

**使用方法:**
```
drupal generate:controller [options]
gcon
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 控制器类名
--routes | 路由(s)必须是包含 [title, method, path] 的数组
--services | 从容器加载服务。
--test | 生成一个测试类

## 例子
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
