# create:vocabularies
Создание фиктивных словарей для Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:vocabularies [options]
crv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Сколько словарей вы хотите создать
--name-words | Максимальное количество слов в именах словарей

## application.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
