# create:terms
Tesztkifejezések létrehozása egy Drupal 8 alkalmazáshoz.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Hány szó jöjjön létre
--name-words | A kifejezések által tartalmazott szavak maximális száma

## Available arguments
Argument | Details
---------|-------------
vocabularies | A kifejezések létrehozásakor használandó szótárak

## Examples
* Provide the vocabulary term name.
```
drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
