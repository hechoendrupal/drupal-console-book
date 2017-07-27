# create:vocabularies
Crea vocabularios de prueba para tu Drupal 8.

**Uso:**
```
drupal create:vocabularies [options]
crv
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--limit | Cuántos vocabularios le gustaría crear
--name-words | Número máximo de palabras en los nombres de vocabulario

## Ejemplos
* Facilitar el número de vocabularios a crear y el número máximo de palabras en los nombres de vocabulario.
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
