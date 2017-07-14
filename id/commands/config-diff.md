# config:diff
Keluaran item konfigurasi aktif yang berbeda dibandingkan dengan pada direktori.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | Lihat perubahan secara terbalik (yaitu membandingkan direktori kepada konfigurasi aktif).

## Available arguments
Argument | Details
---------|-------------
directory | Direktori pembanding. Jika hilang, pilih dari direktori konfigurasi Drupal.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
