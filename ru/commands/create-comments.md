# create:comments
Создание фиктивных комментариев для Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:comments [arguments] [options]
crc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Сколько комментариев вы хотите создать
--title-words | Максимальное количество слов в заголовках комментариев
--time-range | Как далеко назад во времени материалы должны быть датированы

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
node-id | Идентификатор материала для которого будут созданы комментарии

## application.gitbook.messages.examples
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
