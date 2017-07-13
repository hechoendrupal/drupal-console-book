# create:nodes
Teszttartalom létrehozása egy Drupal 8 alkalmazáshoz.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:nodes [arguments] [options]
$ crn  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | Hány tartalom jöjjön létre
--title-words | A tartalom címei által tartalmazott szavak maximális száma
--time-range | Mennyire legyen visszadátumozva a tartalom?
--language | commands.create.nodes.options.language

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-types | A tartalom létrehozásakor használandó tartalomtípusok

## commands.generate.doc.gitbook.messages.examples
* Provide the content type name.
```
$ drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
$ drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"

```
