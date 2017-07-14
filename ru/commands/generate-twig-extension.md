# generate:twig:extension
Generate a Twig extension.

**Usage:**
```
drupal generate:twig:extension [options]
gte
```

## Available options
Option | Details
-------|-------------
--module | Имя модуля.
--name | Twig Extension name
--class | Class name
--services | Загрузка сервисов из контейнера.

## Examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
