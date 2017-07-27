# translation:pending
Determina cadenas de traducción pendientes en un idioma o en un archivo específico de un idioma

**Uso:**
```
drupal translation:pending [arguments] [options]
tp
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | Archivo específico con el que determinar las traducciones pendientes contra el inglés

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Language to determine pending translations against English
library | Library to determine pending translations against English i.e console-yaml

## Ejemplos
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
