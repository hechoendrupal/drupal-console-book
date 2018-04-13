# develop:translation:sync
Sync translation files

**Использование:**
```
drupal develop:translation:sync [arguments] [options]
tsy
```

## Доступные параметры
Команда | Детали
-------|-------------
--file | commands.develop.translation.stats.options.file

## Доступные аргументы
Аргумент | Детали
---------|-------------
language | Language to syncronize against English source files
library | Library to syncronize against English i.e console-yaml

## Примеры
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
