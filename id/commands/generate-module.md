# generate:module
Hasilkan modul.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | Nama modul
--machine-name | Nama mesin (hanya huruf kecil dan garis bawah)
--module-path | Path dari modul
--description | Deskripsi modul
--core | Versi inti
--package | Paket modul
--module-file | Tambahkan sebuah berkas .module
--features-bundle | Definisikan modul sebagai fitur menggunakan nama bundle Features (Fitur) yang diberikan
--composer | Tambahkan sebuah berkas composer.json
--dependencies | Modul dependensi dipisahkan dengan koma (contohnya context, panels)
--test | Hasilkan kelas tes
--twigtemplate | Generate theme template

## Examples
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
