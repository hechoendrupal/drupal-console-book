# create:nodes
Создание фиктивных материалов для Drupal 8.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | Сколько материалов вы хотите создать
--title-words | Максимальное количество слов в заголовках материалов
--time-range | Как далеко назад во времени материалы должны быть датированы
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | Тип(ы) содержимого, которые будут использованы при создании материалов

## Examples
* Provide the content type name.
```
drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
