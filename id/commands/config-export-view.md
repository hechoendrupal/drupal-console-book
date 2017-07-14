# config:export:view
Ekspor sebuah view menggunakan format YAML di dalam modul yang disediakan untuk digunakan kembali pada situs web yang lain.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--optional-config | Ekspor view sebagai Konfigurasi YAML yang bersifat opsional pada modul anda
--include-module-dependencies | Masukkan modul prasyarat pada berkas modul YAML info

## Available arguments
Argument | Details
---------|-------------
view-id | ID view

## Examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
