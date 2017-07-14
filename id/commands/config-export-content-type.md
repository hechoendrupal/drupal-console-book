# config:export:content:type
Ekspor tipe konten tertentu dan fieldnya.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--optional-config | Ekspor tipe konten sebagai konfigurasi YAML opsional pada modul anda

## Available arguments
Argument | Details
---------|-------------
content-type | Tipe Kontent yang akan di ekspor

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
