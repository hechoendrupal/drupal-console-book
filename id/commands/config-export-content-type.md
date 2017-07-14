# config:export:content:type
Ekspor tipe konten tertentu dan fieldnya.

**application.gitbook.messages.usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Nama modul.
--optional-config | Ekspor tipe konten sebagai konfigurasi YAML opsional pada modul anda

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-type | Tipe Kontent yang akan di ekspor

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
