# config:export:view
Exportă un view în format YAML în cadrul unui modul pentru a fi reutilizat într-un alt website.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | Numele Modulului.
--optional-config | Exportă view-ul ca un fișier de configurare YAML în modul
--include-module-dependencies | Include dependințele modulului în fișierul info YAML

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
view-id | View ID

## commands.generate.doc.gitbook.messages.examples
* Provide a view id
```
$ drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
$ drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies

```
