# create:vocabularies
Создание фиктивных словарей для Drupal 8.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Сколько словарей вы хотите создать
--name-words | Максимальное количество слов в именах словарей

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
