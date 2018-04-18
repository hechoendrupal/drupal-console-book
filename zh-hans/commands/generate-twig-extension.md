# generate:twig:extension
生成一个 Twig 扩展

**使用方法:**
```
drupal generate:twig:extension [options]
gte
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--name | Twig 扩展名称
--class | 类名
--services | 从容器加载服务。

## 例子
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
