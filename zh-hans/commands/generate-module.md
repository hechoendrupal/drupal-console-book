# generate:module
生成新模块

**使用方法:**
```
drupal generate:module [options]
gm
```

## 可用选项
选项 | 详细信息
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

## 例子
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
