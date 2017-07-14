# create:nodes
Membuat contoh node untuk aplikasi Drupal 8 anda.

**application.gitbook.messages.usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Berapa banyak node yang ingin anda buat
--title-words | Jumlah kata maksimum pada judul node
--time-range | Berapa jauh waktu kebelakang node ini diberikan tanggal
--language | commands.create.nodes.options.language

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-types | Tipe-tipe konten yang akan digunakan dalam pembuatan node

## application.gitbook.messages.examples
* Provide the content type name.
```
drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
