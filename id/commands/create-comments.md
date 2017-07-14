# create:comments
Membuat contoh komentar untuk aplikasi Drupal 8 anda.

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | Berapa banyak komentar yang ingin anda buat
--title-words | Jumlah kata maksimum pada judul komentar
--time-range | Berapa jauh waktu kebelakang komentar ini diberikan tanggal

## Available arguments
Argument | Details
---------|-------------
node-id | Node ID dimana komentar akan dibuat

## Examples
* Provide the node id where the comments will be generated.
```
drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
