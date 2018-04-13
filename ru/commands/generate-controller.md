# generate:controller
Генерирует и регистрирует контроллер

**Использование:**
```
drupal generate:controller [options]
gcon
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класса контроллера
--routes | Маршруты, должны быть представлены массивом содержащим [название, метод, путь]
--services | Загрузка сервисов из контейнера.
--test | Сгенерировать класс тестов

## Примеры
* Сгенерировать контроллер по имени модуля, классу и его маршрутам
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
