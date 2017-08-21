# develop:translation:cleanup
Hacer limpieza de ficheros de traducción

**Uso:**
```
drupal develop:translation:cleanup [arguments]
tc
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
language | Idioma al que hacer limpieza de sus ficheros contra el inglés
library | Librería a la que hacer limpieza de sus archivos contra el inglés, por ejemplo: console-yaml

## Ejemplos
* Eliminar todos los archivos innecesarios en todos los idiomas.
```
drupal translation:cleanup
```
* Eliminar todos los archivos innecesarios en español
```
drupal translation:cleanup es
```
* Eliminar todos los archivos innecesarios en todos los idiomas en la librería console-develop
```
drupal translation:cleanup all console-develop
```
* Eliminar todos los archivos innecesarios en español en la librería console-develop
```
drupal translation:cleanup es console-develop
```
