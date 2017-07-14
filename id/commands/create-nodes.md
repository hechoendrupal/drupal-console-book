# create:nodes
Membuat contoh node untuk aplikasi Drupal 8 anda.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | Berapa banyak node yang ingin anda buat
--title-words | Jumlah kata maksimum pada judul node
--time-range | Berapa jauh waktu kebelakang node ini diberikan tanggal
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | Tipe-tipe konten yang akan digunakan dalam pembuatan node

## Examples
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
