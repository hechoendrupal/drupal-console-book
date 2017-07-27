# config:export:single
Exporta configuración como fichero yml.

**Uso:**
```
drupal config:export:single [options]
ces
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | Nombre del módulo.
--include-dependencies | Exportar dependencias de la configuración también.
--optional | Exportar la configuración como una configuración opcional en formato YAML su módulo
--remove-uuid | Si se utiliza, la configuración será exportada sin clave uuid.
--remove-config-hash | Si se utiliza, la configuración será exportada sin la clave hash por defecto del sitio.

## Ejemplos
* Facilitar el nombre de la configuración que será exportada
```
drupal config:export:single \
  --name=config.settings.name
```
* Eliminar el uuid y/o los hashes de configuración en la exportación de la configuración
```
drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash
```
