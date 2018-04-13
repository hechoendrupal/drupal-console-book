# develop:translation:sync
Sync translation files

**Usage:**
```
drupal develop:translation:sync [arguments] [options]
tsy
```

## Available options
Option | Details
-------|-------------
--file | commands.develop.translation.stats.options.file

## Available arguments
Argument | Details
---------|-------------
language | Language to syncronize against English source files
library | Library to syncronize against English i.e console-yaml

## Examples
* Syncronize translation files in all languages.
```
drupal translation:sync
```
* Syncronize translation files in Spanish language
```
drupal translation:sync es
```
* Syncronize translation files in all languages in console-develop library
```
drupal translation:sync all console-develop
```
* Syncronize translation files in Spanish language in console-develop library
```
drupal translation:sync es console-develop
```
