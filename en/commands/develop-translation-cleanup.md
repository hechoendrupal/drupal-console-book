# develop:translation:cleanup
Clean up translation files

**Usage:**
```
drupal develop:translation:cleanup [arguments]
tc
```

## Available arguments
Argument | Details
---------|-------------
language | Language to clean up files against English
library | Library to clean up files against English i.e console-yaml

## Examples
* Delete all unnecessary files in all languages.
```
drupal translation:cleanup
```
* Delete all unnecessary files in Spanish language
```
drupal translation:cleanup es
```
* Delete all unnecessary files in all languages in console-develop library
```
drupal translation:cleanup all console-develop
```
* Delete all unnecessary files in Spanish language in console-develop library
```
drupal translation:cleanup es console-develop
```
