# create:terms
Создание фиктивных терминов для Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:terms [arguments] [options]
crt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Сколько терминов вы хотите создать
--name-words | Максимальное количество слов в именах терминов

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
vocabularies | Словари, которые будут использованы при создании терминов

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
