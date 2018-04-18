# multisite:new
Sets up the files for a new multisite install.

**Utilização:**
```
drupal multisite:new [arguments] [options]
mun
sn
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--copy-default | Copies existing site from the default install.

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
directory | Name of directory under 'sites' which should be created.
uri | Site URI to add to sites.php.

## Exemplos
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
