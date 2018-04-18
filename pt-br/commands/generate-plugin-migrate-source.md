# generate:plugin:migrate:source
Generate a migrate source plugin

**Utilização:**
```
drupal generate:plugin:migrate:source [options]
gpms
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin class name
--plugin-id | Plugin id
--table | Table to query
--alias | Short alias to refer to the table as
--group-by | Field to group results by
--fields | Fields to export

## Exemplos
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
