# generate:cache:context
Генерирует контекст кеша

**Использование:**
```
drupal generate:cache:context [options]
gcc
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--cache-context | commands.generate.cache.context.options.name
--class | commands.generate.cache.context.options.class
--services | Загрузка сервисов из контейнера.

## Примеры
* Генерирует кеш для контекста по модулю, имени контекста и классу
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
