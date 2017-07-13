# create:comments
Crear comentarios de prueba para tu aplicación en Drupal 8.

**Uso:**
```
$ drupal create:comments [arguments] [options]
$ crc  
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
* Provide the node id where the comments will be generated.
```
$ drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
$ drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"

```
