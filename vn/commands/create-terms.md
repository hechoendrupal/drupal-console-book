# create:terms
Tạo dummy terms cho ứng dụng Drupal 8 của bạn.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Bao nhiêu terms bạn muốn tạo?
--name-words | Maximum number of words in term names

## Available arguments
Argument | Details
---------|-------------
vocabularies | Vocabularie(s) được sử dụng trong terms creation

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
