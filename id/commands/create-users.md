# create:users
Membuat contoh pengguna untuk aplikasi Drupal 8 anda.

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Berapa banyak pengguna yang akan anda buat
--password | Kata sandi yang akan diberikan pada pengguna
--time-range | Berapa jauh waktu kebelakang pengguna ini diberikan tanggal

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | Peran-peran yang akan digunakan dalam pembuatan pengguna

## application.gitbook.messages.examples
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
