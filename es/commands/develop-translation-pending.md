# develop:translation:pending
Determina cadenas de traducción pendientes en un idioma o en un archivo específico de un idioma

**Uso:**
```
drupal develop:translation:pending [arguments] [options]
tp
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | Archivo específico con el que determinar las traducciones pendientes contra el inglés

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Idioma en el que localizar traducciones pendientes contra el inglés
library | Librería en la que localizar traducciones pendientes contra el inglés, por ejemplo: console-yaml

## Ejemplos
* Localiza cadenas pendientes de traducir en todos los idiomas.
```
drupal translation:pending
```
* Localiza cadenas pendientes de traducir en español
```
drupal translation:pending es
```
* Localiza cadenas pendientes de traducir en todos los idiomas dentro de la librería console-develop
```
drupal translation:pending all console-develop
```
* Localiza cadenas pendientes de traducir en español dentro de la librería console-develop
```
drupal translation:pending es console-develop
```
