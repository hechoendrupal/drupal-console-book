# config:export:single
Exportar configuración única como archivo YAML.

**Uso:**
```
$ drupal config:export:single [arguments] [options]
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--directory | Define el directorio de exportación para guardar la configuración.
--include-dependencies | Exportar dependencias de la configuración también.
--module | Nombre del módulo.
--optional-config | Exportar la configuración como una configuración YAML opcional in su módulo
--remove-uuid | commands.config.export.single.options.remove-uuid

## Argumentos disponibles
Argumento | Detalles
---------|-------------
config-name | Nombre de la configuración.
