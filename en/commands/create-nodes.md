# create:nodes
Create dummy nodes for your Drupal 8 application.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | How many nodes would you like to create
--title-words | Maximum number of words in node titles
--time-range | How far back in time should the nodes be dated
--language | commands.create.nodes.options.language

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-types | Content type(s) to be used in node creation

## commands.generate.doc.gitbook.messages.examples
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
