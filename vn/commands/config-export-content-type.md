# config:export:content:type
Xuất một kiểu nội dung chỉ định và các field của chúng

**application.gitbook.messages.usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Tên module.
--optional-config | Xuất loại nội dung như một cấu hình YAML tuỳ chọn trong module của bạn

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-type | Content Type to be exported

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
