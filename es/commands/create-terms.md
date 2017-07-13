# create:terms
Crea términos de relleno para tu Drupal 8.

**Uso:**
```
$ drupal create:terms [arguments] [options]
$ crt  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--limit | Cuántos términos le gustaría crear
--name-words | Número máximo de palabras en los títulos de los términos

## Argumentos disponibles
Argumento | Detalles
---------|-------------
vocabularies | Vocabulario(s) que serán usados en la generación de términos

## Ejemplos
* Provide the vocabulary term name.
```
$ drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
$ drupal create:terms tags \
  --limit="10" \
  --name-words="5"

```
