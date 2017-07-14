# config:export:content:type
导出内容类型及其字段

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--optional-config | 导出内容类型作为模块中的可选配置

## Available arguments
Argument | Details
---------|-------------
content-type | 内容类型

## Examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
