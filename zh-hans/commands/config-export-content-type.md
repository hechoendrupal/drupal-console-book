# config:export:content:type
导出特定的内容类型及其字段。

**使用方法:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--optional-config | 将内容类型导出为模块中的可选 YAML 配置
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## 可用参数
参数 | 详细信息
---------|-------------
content-type | 要导出的内容类型

## 例子
* 提供内容类型和模块名称
```
drupal config:export:content:type page \
  --module="demo"
```
* 如果要导出内容类型提供可选配置
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
