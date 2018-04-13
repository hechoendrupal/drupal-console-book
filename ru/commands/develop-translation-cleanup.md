# develop:translation:cleanup
Очистить файлы переводов

**Использование:**
```
drupal develop:translation:cleanup [arguments]
tc
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
language | Language to clean up files against English
library | Library to clean up files against English i.e console-yaml

## Примеры
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
