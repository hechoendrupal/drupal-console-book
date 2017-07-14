# config:export:view
Exportă un view în format YAML în cadrul unui modul pentru a fi reutilizat într-un alt website.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Numele Modulului.
--optional-config | Exportă view-ul ca un fișier de configurare YAML în modul
--include-module-dependencies | Include dependințele modulului în fișierul info YAML

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | View ID

## application.gitbook.messages.examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
