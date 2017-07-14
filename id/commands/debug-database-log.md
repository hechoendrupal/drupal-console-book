# debug:database:log
Menampilkan log event terkini untuk aplikasi

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | Daftar event dalam urutan naik
--limit | Batasi hasil ke angka tertentu
--offset | Titik mulai dari sebuah batasan
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | ID event DBLog

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
