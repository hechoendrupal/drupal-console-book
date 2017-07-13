# generate:module
生成新模块

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:module [options]
$ gm  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | 模块名
--machine-name | 模块名 (只能用小写英文字母和下划线)
--module-path | 模块路径
--description | 模块说明
--core | Drupal 核心版本
--package | 模块包
--module-file | 添加一个 .module 文件
--features-bundle | 使用给定的 Features bundle 名称定义模块为 Feature
--composer | 添加一个 composer.json 文件
--dependencies | 模块依赖，以逗号分隔 (例如： context, panels)
--test | 生成一个测试类
--twigtemplate | Generate theme template
