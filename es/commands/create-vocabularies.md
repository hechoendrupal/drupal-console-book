# create:vocabularies
Crea vocabularios de prueba para tu Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:vocabularies [options]
crv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Cuántos vocabularios le gustaría crear
--name-words | Número máximo de palabras en los nombres de vocabulario

## application.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
