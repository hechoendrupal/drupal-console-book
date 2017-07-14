# generate:command
Buat perintah console baru.

**Usage:**
```
drupal generate:command [options]
gco
gcm
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | Nama Kelas yang menguraikan perintah ini. (Harus diakhiri dengan kata 'Command').
--name | Nama Perintah ini.
--container-aware | Apakah perintah ini perlu mendeteksi jika situs drupal sudah terpasang sewaktu perintah dijalankan
--services | Memuat servis dari kontainer.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
