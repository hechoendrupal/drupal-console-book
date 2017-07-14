# config:diff
Keluaran item konfigurasi aktif yang berbeda dibandingkan dengan pada direktori.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | Lihat perubahan secara terbalik (yaitu membandingkan direktori kepada konfigurasi aktif).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | Direktori pembanding. Jika hilang, pilih dari direktori konfigurasi Drupal.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
