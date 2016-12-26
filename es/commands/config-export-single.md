# config:export:single
Exportar configuración única como archivo YAML.

**Uso:**
```
$ drupal config:export:single [options]
$ ces  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--name | commands.config.export.single.options.name
--directory | Define el directorio de exportación para guardar la configuración.
--module | Nombre del módulo.
--include-dependencies | Exportar dependencias de la configuración también.
--optional | Exportar la configuración como una configuración opcional en formato YAML su módulo
--remove-uuid | Si se utiliza, la configuración será exportada sin clave uuid.
--remove-config-hash | Si se utiliza, la configuración será exportada sin la clave hash por defecto del sitio.
