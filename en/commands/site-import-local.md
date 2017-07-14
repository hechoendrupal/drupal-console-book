# site:import:local
Import/Configure an existing local Drupal project

**application.gitbook.messages.usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--environment | Name of the environment that is going to be imported

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Name that will be used to generate the site config
directory | Existing Drupal root directory

## application.gitbook.messages.examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
