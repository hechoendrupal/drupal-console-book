# generate:twig:extension
Генерирует Twig расширение.

**Использование:**
```
drupal generate:twig:extension [options]
gte
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--name | Имя Twig расширения
--class | Имя класса
--services | Загрузка сервисов из контейнера.

## Примеры
* Генерирует twig расширение по имени модуля, имени расширения и его классу
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
