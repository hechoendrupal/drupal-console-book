# create:users
Membuat contoh pengguna untuk aplikasi Drupal 8 anda.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | Berapa banyak pengguna yang akan anda buat
--password | Kata sandi yang akan diberikan pada pengguna
--time-range | Berapa jauh waktu kebelakang pengguna ini diberikan tanggal

## Available arguments
Argument | Details
---------|-------------
roles | Peran-peran yang akan digunakan dalam pembuatan pengguna

## Examples
* Provide the user role.
```
drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
