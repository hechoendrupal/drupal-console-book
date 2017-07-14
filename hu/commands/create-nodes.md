# create:nodes
Teszttartalom létrehozása egy Drupal 8 alkalmazáshoz.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | Hány tartalom jöjjön létre
--title-words | A tartalom címei által tartalmazott szavak maximális száma
--time-range | Mennyire legyen visszadátumozva a tartalom?
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | A tartalom létrehozásakor használandó tartalomtípusok

## Examples
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
