# config:export:content:type
コンテンツタイプとフィールドをエクスポート

**application.gitbook.messages.usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | モジュール名
--optional-config | Export content type as an optional YAML configuration in your module

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-type | エクスポートするコンテンツタイプ

## application.gitbook.messages.examples
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
