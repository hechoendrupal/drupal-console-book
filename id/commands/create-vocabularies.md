# create:vocabularies
Membuat contoh vocabularies untuk aplikasi Drupal 8 anda.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Berapa banyak vocabularies yang akan anda buat
--name-words | Jumlah kata maksimum dalam nama vocabulary

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
