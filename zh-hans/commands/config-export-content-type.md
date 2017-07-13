# config:export:content:type
导出内容类型及其字段

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:content:type [arguments] [options]
$ cect  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | 模块名称
--optional-config | 导出内容类型作为模块中的可选配置

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-type | 内容类型

## commands.generate.doc.gitbook.messages.examples
* Provide a content type  and module name
```
$ drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
$ drupal config:export:content:type page \
  --module="demo" \
  --optional-config 

```
