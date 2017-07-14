# create:comments
Создание фиктивных комментариев для Drupal 8.

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | Сколько комментариев вы хотите создать
--title-words | Максимальное количество слов в заголовках комментариев
--time-range | Как далеко назад во времени материалы должны быть датированы

## Available arguments
Argument | Details
---------|-------------
node-id | Идентификатор материала для которого будут созданы комментарии

## Examples
* Provide the node id where the comments will be generated.
```
drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
