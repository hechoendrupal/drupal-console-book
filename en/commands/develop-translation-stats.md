# develop:translation:stats
Calcuate translation stats

**Usage:**
```
drupal develop:translation:stats [arguments] [options]
ts
```

## Available options
Option | Details
-------|-------------
--format | Define output format table|markdown

## Available arguments
Argument | Details
---------|-------------
language | Language to calculate translation stats against English
library | Library to calculate translation stats against English i.e console-yaml

## Examples
* Calculate translation stats in all languages.
```
drupal translation:stats
```
* Calculate translation stats in Spanish language
```
drupal translation:stats es
```
* Calculate translation stats in all languages in console-develop library
```
drupal translation:stats all console-develop
```
* Calculate translation stats in Spanish language in console-develop library
```
drupal translation:stats es console-develop
```
