# multisite:new
Sets up the files for a new multisite install.

**Ús:**
```
drupal multisite:new [arguments] [options]
mun
sn
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--copy-default | Copies existing site from the default install.

## Arguments disponibles
Argument | Detalls
---------|-------------
directory | Name of directory under 'sites' which should be created.
uri | Site URI to add to sites.php.

## Exemples
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
