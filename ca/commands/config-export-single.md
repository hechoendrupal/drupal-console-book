# config:export:single
Exportar la configuració com a fitxer YML

**Ús:**
```
drupal config:export:single [options]
ces
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | Nom del mòdul.
--include-dependencies | Exportar també les dependències de la configuració.
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Exemples
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
