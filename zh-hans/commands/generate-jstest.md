# generate:jstest
Generate a JavaScript test.

**使用方法:**
```
drupal generate:jstest [options]
gjt
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | JavaScript test Class name

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
