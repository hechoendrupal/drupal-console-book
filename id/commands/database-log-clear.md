# database:log:clear
Hapus events dari tabel DBlog, filter tersedia

**application.gitbook.messages.usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filter event oleh jenis tertentu
--severity | Filter event oleh tingkat keparahan
--user-id | Filter event oleh ID pengguna tertentu

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID event DBLog

## application.gitbook.messages.examples
* Clear the database log from DBLog table
```
drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
