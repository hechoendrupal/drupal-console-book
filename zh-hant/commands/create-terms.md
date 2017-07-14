# create:terms
Create dummy terms for your Drupal 8 application.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | How many terms would you like to create
--name-words | Maximum number of words in term names

## Available arguments
Argument | Details
---------|-------------
vocabularies | Vocabulary(s) to be used in terms creation

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
