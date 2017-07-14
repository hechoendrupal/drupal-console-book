# create:vocabularies
Membuat contoh vocabularies untuk aplikasi Drupal 8 anda.

**application.gitbook.messages.usage:**
```
drupal create:vocabularies [options]
crv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Berapa banyak vocabularies yang akan anda buat
--name-words | Jumlah kata maksimum dalam nama vocabulary

## application.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
