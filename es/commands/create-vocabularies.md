# create:vocabularies
Crea vocabularios de prueba para tu Drupal 8.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Cuántos vocabularios le gustaría crear
--name-words | Número máximo de palabras en los nombres de vocabulario

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
