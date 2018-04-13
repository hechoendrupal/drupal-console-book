# develop:translation:pending
Determine pending translation string in a language or a specific file in a language

**Использование:**
```
drupal develop:translation:pending [arguments] [options]
tp
```

## Доступные параметры
Команда | Детали
-------|-------------
--file | Specific file to determine pending translations against English

## Доступные аргументы
Аргумент | Детали
---------|-------------
language | Language to determine pending translations against English
library | Library to determine pending translations against English i.e console-yaml

## Примеры
* Determine pending translation strings in all languages.
```
drupal translation:pending
```
* Determine pending translation strings in Spanish language
```
drupal translation:pending es
```
* Determine pending translation strings in all languages in console-develop library
```
drupal translation:pending all console-develop
```
* Determine pending translation strings in Spanish language in console-develop library
```
drupal translation:pending es console-develop
```
