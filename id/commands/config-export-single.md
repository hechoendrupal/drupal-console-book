# config:export:single
Ekspor konfigurasi tunggal sebagai berkas yml.

**application.gitbook.messages.usage:**
```
drupal config:export:single [options]
ces
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--name | commands.config.export.single.options.name
--directory | Mendefinisikan direktori ekspor untuk menyimpan keluaran konfigurasi.
--module | Nama modul.
--include-dependencies | Ekspor prasyarat dari konfigurasi.
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## application.gitbook.messages.examples
* Provide config settings name to be exported
```
drupal config:export:single \
  --name=config.settings.name
```
* if uuid and/or config hashes will be removed.
```
drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash
```
