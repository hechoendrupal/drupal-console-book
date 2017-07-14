# create:terms
Membuat contoh terms untuk aplikasi Drupal 8 anda.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Berapa banyak term yang akan anda buat
--name-words | Jumlah kata maksimum dalam nama terms

## Available arguments
Argument | Details
---------|-------------
vocabularies | Vocabulary yang akan dibuat dalam pembuatan terms

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
