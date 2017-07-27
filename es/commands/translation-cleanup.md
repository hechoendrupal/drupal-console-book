# translation:cleanup
Ficheros de limpieza de traducción

**Uso:**
```
drupal translation:cleanup [arguments]
tc
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Idioma al que hacer limpieza de sus ficheros contra el inglés
library | Library to clean up files against English i.e console-yaml

## Ejemplos
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
