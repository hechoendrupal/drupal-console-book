# create:terms
Создание фиктивных терминов для Drupal 8.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Сколько терминов вы хотите создать
--name-words | Максимальное количество слов в именах терминов

## Available arguments
Argument | Details
---------|-------------
vocabularies | Словари, которые будут использованы при создании терминов

## Examples
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
