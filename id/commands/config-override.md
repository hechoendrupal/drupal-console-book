# config:override
Menimpa nilai konfigurasi pada konfigurasi aktif.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Nama konfigurasi
key | Key
value | Value

## application.gitbook.messages.examples
* Atur flood limit pada modul Contact menjadi 10.
```
drupal config:override contact.settings flood.limit 10
```
