# config:override
Menimpa nilai konfigurasi pada konfigurasi aktif.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Nama konfigurasi
key | Key
value | Value

## Examples
* Atur flood limit pada modul Contact menjadi 10.
```
drupal config:override contact.settings flood.limit 10
```
