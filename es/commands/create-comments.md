# create:comments
Crear comentarios de prueba para tu aplicación en Drupal 8.

**Uso:**
```
drupal create:comments [arguments] [options]
crc
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--limit | ¿Cuántos comentarios quiere crear?
--title-words | ¿Cuál es el número máximo de palabras en los títulos de los comentarios?
--time-range | ¿Cuán atrás en el tiempo se deben crear los comentarios?

## Argumentos disponibles
Argumento | Detalles
---------|-------------
node-id | El ID del nodo en donde se crearán los comentarios

## Ejemplos
* Facilitar el id de nodo para el que se generarán los comentarios.
```
drupal create:comments  node-id
```
* Facilitar el número de comentarios a generar, con un máximo de palabras en el título y un rango de tiempo.
```
drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
