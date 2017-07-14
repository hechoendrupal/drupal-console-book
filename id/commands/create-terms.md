# create:terms
Membuat contoh terms untuk aplikasi Drupal 8 anda.

**application.gitbook.messages.usage:**
```
drupal create:terms [arguments] [options]
crt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Berapa banyak term yang akan anda buat
--name-words | Jumlah kata maksimum dalam nama terms

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
vocabularies | Vocabulary yang akan dibuat dalam pembuatan terms

## application.gitbook.messages.examples
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
