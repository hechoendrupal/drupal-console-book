# develop:translation:sync
Sincronizar archivos de traducción

**Uso:**
```
drupal develop:translation:sync [arguments] [options]
tsy
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | commands.develop.translation.stats.options.file

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Idioma cuyos ficheros se sincronizarán contra el inglés
library | Librería a sincronizar contra el idioma inglés, por ejemplo: console-yaml

## Ejemplos
* Sincronizar archivos de traducción en todos los idiomas.
```
drupal translation:sync
```
* Sincronizar archivos de traducción en español
```
drupal translation:sync es
```
* Sincronizar archivos de traducción en todos los idiomas en la librería console-develop
```
drupal translation:sync all console-develop
```
* Sincronizar archivos de traducción en español en la librería console-develop
```
drupal translation:sync es console-develop
```
