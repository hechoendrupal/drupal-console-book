# create:nodes
Crea nodos de relleno para su Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | ¿Cuántos nodos le gustaría crear?
--title-words | Número máximo de palabras en el título de los nodos
--time-range | Desde cuándo deberían ser fechados los nodos
--language | commands.create.nodes.options.language

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-types | Tipo(s) de contenido que desea generar

## application.gitbook.messages.examples
* Provide the content type name.
```
drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
