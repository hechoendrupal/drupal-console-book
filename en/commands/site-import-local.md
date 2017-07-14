# site:import:local
Import/Configure an existing local Drupal project

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal site:import:local [arguments] [options]
$ sil
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--environment | Name of the environment that is going to be imported

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | Name that will be used to generate the site config
directory | Existing Drupal root directory

## commands.generate.doc.gitbook.messages.examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
