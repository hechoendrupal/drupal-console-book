# database:log:clear
Hapus events dari tabel DBlog, filter tersedia

**Usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Available options
Option | Details
-------|-------------
--type | Filter event oleh jenis tertentu
--severity | Filter event oleh tingkat keparahan
--user-id | Filter event oleh ID pengguna tertentu

## Available arguments
Argument | Details
---------|-------------
event-id | ID event DBLog

## Examples
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
