# config:export:content:type
Exportar um content-type específico e todos os seus fields.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:content:type [arguments] [options]
$ cect  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | O nome do módulo.
--optional-config | Exportar o content-type como uma configuração YAML opcional em seu módulo.

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-type | Content Type to be exported

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
