# develop:translation:stats
Genera estadísticas de traducción

**Uso:**
```
drupal develop:translation:stats [arguments] [options]
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
library | Librería para la que generar estadísticas de traducción contra el idioma inglés, por ejemplo: console-yaml

## Ejemplos
* Calcular estadísticas de traducción en todos los idiomas.
```
drupal translation:stats
```
* Calcular estadísticas de traducción en español
```
drupal translation:stats es
```
* Calcular estadísticas de traducción en todos los idiomas en la librería console-develop
```
drupal translation:stats all console-develop
```
* Calcular estadísticas de traducción en español en la librería console-develop
```
drupal translation:stats es console-develop
```
