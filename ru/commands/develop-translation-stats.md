# develop:translation:stats
Generate translate stats

**Использование:**
```
drupal develop:translation:stats [arguments] [options]
ts
```

## Доступные параметры
Команда | Детали
-------|-------------
--format | Define output format table|markdown

## Доступные аргументы
Аргумент | Детали
---------|-------------
language | Language to generate translation stats against English
library | Library to calculate translation stats against English i.e console-yaml

## Примеры
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
