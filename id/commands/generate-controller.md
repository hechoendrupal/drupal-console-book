# generate:controller
Buat dan daftarkan controller

**Usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Nama Kelas Controller
--routes | Semua route, harus berupa array yang berisi [nama, metode, path]
--services | Memuat servis dari kontainer.
--test | Buat kelas untuk unit test

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
