# generate:controller
生成并注册新控制器

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:controller [options]
$ gcn  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | 模块名称
--class | 控制器类名
--routes | 路由(s)必须是包含 [title, method, path] 的数组
--services | 从容器中导入服务
--test | 生成一个测试类
