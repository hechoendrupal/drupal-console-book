# config:export:content:type
Xuất một kiểu nội dung chỉ định và các field của chúng

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--optional-config | Xuất loại nội dung như một cấu hình YAML tuỳ chọn trong module của bạn
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Available arguments
Argument | Details
---------|-------------
content-type | Content Type to be exported

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
