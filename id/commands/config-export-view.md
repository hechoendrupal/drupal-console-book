# config:export:view
Ekspor sebuah view menggunakan format YAML di dalam modul yang disediakan untuk digunakan kembali pada situs web yang lain.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Nama modul.
--optional-config | Ekspor view sebagai Konfigurasi YAML yang bersifat opsional pada modul anda
--include-module-dependencies | Masukkan modul prasyarat pada berkas modul YAML info

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | ID view

## application.gitbook.messages.examples
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
