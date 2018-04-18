# config:export:view
在提供的模块中导出 YAML 格式的视图，以便在其他网站中重复使用。

**使用方法:**
```
drupal config:export:view [arguments] [options]
cev
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--optional-config | 将配置导出为模块中的可选 YAML 配置
--include-module-dependencies | 在模块信息 YAML 文件中包含视图模块依赖关系

## 可用参数
参数 | 详细信息
---------|-------------
view-id | 视图 ID

## 例子
* 提供视图ID
```
drupal config:export:view viewid
```
* 您可以提供交互式值，如参数。
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
