# generate:plugin:migrate:source
माइग्रेट स्रोत प्लगइन उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:migrate:source [options]
gpms
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--plugin-id | प्लगिन आयडी
--table | क्वेरीसाठी टेबल.
--alias | सारणीचा सारांश म्हणून लघु उपनाव.
--group-by | फील्ड द्वारे गट परिणाम.
--fields | निर्यात करण्यासाठी फील्ड.

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
