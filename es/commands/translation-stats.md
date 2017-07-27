# translation:stats
Genera estadísticas de traducción

**Uso:**
```
drupal translation:stats [arguments] [options]
ts
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--format | Define el formato de salida ( table|markdown )

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Idioma para generar estadísticas de traducción contra el inglés
library | Library to generate translation stats against English i.e console-yaml

## Ejemplos
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
