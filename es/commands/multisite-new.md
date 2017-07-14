# multisite:new
Prepara los archivos para una nueva instalación multisitio.

**Usage:**
```
drupal multisite:new [arguments] [options]
mun
```

## Available options
Option | Details
-------|-------------
--copy-default | Copia un sitio existente desde la instalación por defecto.

## Available arguments
Argument | Details
---------|-------------
directory | Nombre del directorio bajo 'sites' que será creado.
uri | URI del sitio que se añadirá al sites.php.

## Examples
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
