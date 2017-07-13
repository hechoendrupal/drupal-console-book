# create:vocabularies
Crea vocabularios de prueba para tu Drupal 8.

**Uso:**
```
$ drupal create:vocabularies [options]
$ crv  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--limit | Cuántos vocabularios le gustaría crear
--name-words | Número máximo de palabras en los nombres de vocabulario

## Ejemplos
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
$ drupal create:vocabularies \
  --limit="5" \
  --name-words="5"

```
