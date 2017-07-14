# generate:plugin:migrate:source
Genera un plugin de migración de fuentes

**Usage:**
```
drupal generate:plugin:migrate:source [options]
gpms
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--plugin-id | ID del Plugin
--table | Tabla a hacer el query
--alias | Alias corto para referirse a la tabla
--group-by | Campo por el que agrupar los resultados
--fields | Campos a exportar

## Examples
* Generate a migration source plugin specifying the module name, the class, its plugin id, the table and its alias
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="PluginClassName"  \
  --plugin-id="plugin_class_name"  \
  --table="DefaultTableName"  \
  --alias="D"
```
* Generate a migration source plugin for specific fields of the users table specifying the module name, the class, its plugin id, the table, its alias and the fields
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
