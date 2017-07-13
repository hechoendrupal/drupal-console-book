# config:export:content:type
Xuất một kiểu nội dung chỉ định và các field của chúng

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:content:type [arguments] [options]
$ cect  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | Tên module.
--optional-config | Xuất loại nội dung như một cấu hình YAML tuỳ chọn trong module của bạn

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-type | Content Type to be exported

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
