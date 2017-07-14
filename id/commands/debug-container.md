# debug:container
Menampilkan servis terkini untuk aplikasi.

**Usage:**
```
drupal debug:container [arguments] [options]
dco
```

## Available options
Option | Details
-------|-------------
--parameters | Nama Servis.

## Available arguments
Argument | Details
---------|-------------
service | Nama Servis.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
