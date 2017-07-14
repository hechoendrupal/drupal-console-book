# create:terms
Crea términos de relleno para tu Drupal 8.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Cuántos términos le gustaría crear
--name-words | Número máximo de palabras en los títulos de los términos

## Available arguments
Argument | Details
---------|-------------
vocabularies | Vocabulario(s) que serán usados en la generación de términos

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
