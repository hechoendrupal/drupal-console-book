# config:export:single
Exporta configuración como fichero yml.

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
--module | Nombre del módulo.
--include-dependencies | Exportar dependencias de la configuración también.
--optional | Exportar la configuración como una configuración opcional en formato YAML su módulo
--remove-uuid | Si se utiliza, la configuración será exportada sin clave uuid.
--remove-config-hash | Si se utiliza, la configuración será exportada sin la clave hash por defecto del sitio.

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
