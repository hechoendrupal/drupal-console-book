# create:terms
Crear termes 'dummy' per l'aplicació Drupal 8.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Quants termes voldrieu crear
--name-words | Màxim de paraules dels noms del termes

## Available arguments
Argument | Details
---------|-------------
vocabularies | Vocabulari utilitzat en la creació termes

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
