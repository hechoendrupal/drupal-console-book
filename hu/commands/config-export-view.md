# config:export:view
Nézet exportálása YAML-formátumban egy megadott modulba, hogy újra lehessen használni más weboldalon.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | A modul neve.
--optional-config | Nézet exportálása a modulba nem kötelező YAML-konfigurációként
--include-module-dependencies | Modulfüggőségeinek tartalmazása a modul info.yml fájljában

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
view-id | Nézet azonosítója

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
