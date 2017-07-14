# multisite:new
Sets up the files for a new multisite install.

**application.gitbook.messages.usage:**
```
drupal multisite:new [arguments] [options]
mun
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--copy-default | Copies existing site from the default install.

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | Name of directory under 'sites' which should be created.
uri | Site URI to add to sites.php.

## application.gitbook.messages.examples
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
