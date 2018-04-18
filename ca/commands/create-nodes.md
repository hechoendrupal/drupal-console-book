# create:nodes
Crear nodes 'dummy' per l'aplicació Drupal 8.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | Quants nodes voldrieu crear
--title-words | Màxim de pararules dels títols de nodes
--time-range | Quant de temps enrere ha de ser la data dels nodes
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | Tipus de continguts utilitzats en la creació de nodes

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
