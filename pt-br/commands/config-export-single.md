# config:export:single
Exportar configuração como um arquivo yml.

**Utilização:**
```
drupal config:export:single [options]
ces
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | O nome do módulo.
--include-dependencies | Export dependencies of the configuration as well.
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Exemplos
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
