# create:nodes
Crea nodos de relleno para su Drupal 8.

**Uso:**
```
drupal create:nodes [arguments] [options]
crn
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--limit | ¿Cuántos nodos le gustaría crear?
--title-words | Número máximo de palabras en el título de los nodos
--time-range | Desde cuándo deberían ser fechados los nodos
--language | commands.create.nodes.options.language

## Argumentos disponibles
Argumento | Detalles
---------|-------------
content-types | Tipo(s) de contenido que desea generar

## Ejemplos
* Facilitando el nombre de tipo de contenido.
```
drupal create:nodes content-name
```
* Facilitando el límite de publicaciones, de palabras en el título, con rango de tiempo e idioma.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
