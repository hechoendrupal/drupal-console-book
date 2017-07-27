# generate:plugin:migrate:source
Genera un plugin de migración de fuentes

**Uso:**
```
drupal generate:plugin:migrate:source [options]
gpms
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--plugin-id | ID del Plugin
--table | Tabla a hacer el query
--alias | Alias corto para referirse a la tabla
--group-by | Campo por el que agrupar los resultados
--fields | Campos a exportar

## Ejemplos
* Generar un plugin de migración de fuentes especificando el nombre del módulo, la clase, su id de plugin, la tabla y su alias
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="PluginClassName"  \
  --plugin-id="plugin_class_name"  \
  --table="DefaultTableName"  \
  --alias="D"
```
* Generar un plugin de migración de fuentes para campos específicos de la tabla de usuarios especificando el nombre del módulo, la clase, el id de plugin, la tabla, su alias y los campos
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="DefaultPluginClass"  \
  --plugin-id="default_plugin_class"  \
  --table="users"  \
  --alias="u"  \
  --fields='"id":"id", "description":"the user id"'  \
  --fields='"id":"username", "description":"the username"'  \
  --fields='"id":"password", "description":"the user password"'  \
  --fields='"id":"email", "description":"the user email"'
```
