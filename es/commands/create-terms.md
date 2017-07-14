# create:terms
Crea términos de relleno para tu Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:terms [arguments] [options]
crt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Cuántos términos le gustaría crear
--name-words | Número máximo de palabras en los títulos de los términos

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
vocabularies | Vocabulario(s) que serán usados en la generación de términos

## application.gitbook.messages.examples
* Provide the vocabulary term name.
```
drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
