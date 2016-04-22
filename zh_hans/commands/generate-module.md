# generate:module
生成新模块

**用法:**
```
$ drupal generate:module [options]
$ gm  
```

## 可用选项
选项 | 详细
-------|-------------
--module | 模块名
--machine-name | 模块名 (只能用小写英文字母和下划线)
--module-path | 模块路径
--description | 模块说明
--core | Drupal 核心版本
--package | 模块包
--module-file | 添加一个 .module 文件
--features-bundle | Define module as feature using the given Features bundle name
--composer | 添加一个 composer.json 文件
--dependencies | 模块依赖，以逗号分隔 (例如： context, panels)
