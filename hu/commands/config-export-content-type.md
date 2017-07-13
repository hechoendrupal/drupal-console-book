# config:export:content:type
Adott tartalomtípus és mezőinek exportálása.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:content:type [arguments] [options]
$ cect  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | A modul neve.
--optional-config | Tartalomtípus exportálása a modulba nem kötelező YAML-konfigurációként

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-type | Az exportálni kívánt tartalomtípus

## commands.generate.doc.gitbook.messages.examples
* Provide a content type  and module name
```
$ drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
$ drupal config:export:content:type page \
  --module="demo" \
  --optional-config 

```
