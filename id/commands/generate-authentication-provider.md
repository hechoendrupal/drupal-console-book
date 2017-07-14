# generate:authentication:provider
Hasilkan penyedia otentikasi

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Kelas Penyedia Otentikasi
--provider-id | ID Penyedia

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
