# debug:database:log
Menampilkan log event terkini untuk aplikasi

**application.gitbook.messages.usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | Daftar event dalam urutan naik
--limit | Batasi hasil ke angka tertentu
--offset | Titik mulai dari sebuah batasan
--yml | Print in a yml style

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID event DBLog
