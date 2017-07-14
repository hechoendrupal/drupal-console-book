# config:export:view
Nézet exportálása YAML-formátumban egy megadott modulba, hogy újra lehessen használni más weboldalon.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | A modul neve.
--optional-config | Nézet exportálása a modulba nem kötelező YAML-konfigurációként
--include-module-dependencies | Modulfüggőségeinek tartalmazása a modul info.yml fájljában

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | Nézet azonosítója

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
