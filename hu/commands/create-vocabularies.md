# create:vocabularies
Tesztszótárak létrehozása egy Drupal 8 alkalmazáshoz.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Hány szótár jöjjön létre?
--name-words | A szótárak nevében használt szavak maximális száma

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
