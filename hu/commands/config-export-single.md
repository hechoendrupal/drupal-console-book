# config:export:single
Egyetlen konfigurációs fájl exportálása yml-fájlként.

**Usage:**
```
drupal config:export:single [options]
ces
```

## Available options
Option | Details
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | A modul neve.
--include-dependencies | A konfiguráció függőségei is legyenek exportálva.
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Examples
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
