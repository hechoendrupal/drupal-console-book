# generate:event:subscriber
Генерирует подписчик на событие

**Использование:**
```
drupal generate:event:subscriber [options]
ges
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--name | commands.generate.event.subscriber.options.name
--class | commands.generate.event.subscriber.options.class
--events | Загрузить события из контейнера
--services | Загрузка сервисов из контейнера.

## Примеры
* Генерирует подписчик на события по имени модуля, имени, классу и листу событий для подписания
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
