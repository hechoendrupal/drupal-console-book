# config:export:view
导出视图

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--optional-config | 导出视图作为模块的可选配置
--include-module-dependencies | 在模块的 info 文件中包含相关依赖模块

## Available arguments
Argument | Details
---------|-------------
view-id | 视图 ID

## Examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
