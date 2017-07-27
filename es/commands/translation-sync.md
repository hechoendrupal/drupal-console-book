# translation:sync
Sincronizar archivos de traducción

**Uso:**
```
drupal translation:sync [arguments] [options]
tsy
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | commands.translation.stats.options.file

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Idioma cuyos ficheros se sincronizarán contra el inglés
library | Library to syncronize against English i.e console-yaml

## Ejemplos
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
