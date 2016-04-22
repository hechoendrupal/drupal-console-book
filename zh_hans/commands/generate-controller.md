# generate:controller
生成并注册新控制器

**用法:**
```
$ drupal generate:controller [options]
$ gcn  
```

## 可用选项
选项 | 详细
-------|-------------
--module | 模块名称
--class | 控制器类名
--routes | 路由(s)必须是包含 [title, method, path] 的数组
--services | 从容器中导入服务
--test | 生成一个测试类
