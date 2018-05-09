# multisite:new
Prépare les fichiers pour une nouvelle installation multi-sites.

**Usage:**
```
drupal multisite:new [arguments] [options]
mun
sn
```

## Available options
Option | Details
-------|-------------
--copy-default | Copies existing site from the default install.

## Available arguments
Argument | Details
---------|-------------
directory | Name of directory under 'sites' which should be created.
uri | Site URI to add to sites.php.

## Examples
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
