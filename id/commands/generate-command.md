# generate:command
Buat perintah console baru.

**application.gitbook.messages.usage:**
```
drupal generate:command [options]
gco
gcm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | Nama Kelas yang menguraikan perintah ini. (Harus diakhiri dengan kata 'Command').
--name | Nama Perintah ini.
--container-aware | Apakah perintah ini perlu mendeteksi jika situs drupal sudah terpasang sewaktu perintah dijalankan
--services | Memuat servis dari kontainer.
