# config:export:content:type
コンテンツタイプとフィールドをエクスポート

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | モジュール名
--optional-config | Export content type as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Available arguments
Argument | Details
---------|-------------
content-type | エクスポートするコンテンツタイプ

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
