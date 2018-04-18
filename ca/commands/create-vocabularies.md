# create:vocabularies
Crear vocabulari 'dummy' per l'aplicació Drupal 8.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Quants vocabularis voldrieu crear
--name-words | Màxim de paraules utilitzades al nom del vocabulari

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
