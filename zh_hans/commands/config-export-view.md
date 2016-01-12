# config:export:view
**config:export:view** 命令 导出一个视窗配置到一个模块里的YAML格式文件，这样其他网站也可以使用它.

**用法:**
```
$ drupal config:export:view [arguments] [options] 
$ cev  
```

## 可用选项
选项 | 详细
-------|-------------
--module | 模块名称
--optional-config | 把导出视窗作为一个YAML文件配置的选项
--include-module-dependencies | 在模块配置YAML文件里包含视窗模块所依赖的组件

## 可用参数
参数 | 详细
---------|-------------
view-id | 视窗ID
