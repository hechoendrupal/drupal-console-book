# generate:routesubscriber
Генерирует RouteSubscriber

**Использование:**
```
drupal generate:routesubscriber [options]
gr
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--name | Имя сервиса
--class | Имя класса

## Примеры
* Генерирует RouteSubscriber по имени модуля, маршруту и его классу
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
