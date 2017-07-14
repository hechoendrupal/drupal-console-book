# multisite:new
Sets up the files for a new multisite install.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal multisite:new [arguments] [options]
$ mun
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--copy-default | Copies existing site from the default install.

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
directory | Name of directory under 'sites' which should be created.
uri | Site URI to add to sites.php.

## commands.generate.doc.gitbook.messages.examples
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
