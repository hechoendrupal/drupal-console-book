# create:nodes
Teszttartalom létrehozása egy Drupal 8 alkalmazáshoz.

**application.gitbook.messages.usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Hány tartalom jöjjön létre
--title-words | A tartalom címei által tartalmazott szavak maximális száma
--time-range | Mennyire legyen visszadátumozva a tartalom?
--language | commands.create.nodes.options.language

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-types | A tartalom létrehozásakor használandó tartalomtípusok

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
