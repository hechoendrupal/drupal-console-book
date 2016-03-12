# generate:controller
The **generate:controller** command Generate & Register a controller

**Использование:**
```
$ drupal generate:controller [options] 
$ gcn  
```

## Доступные опции
Опция | Описание
-------|-------------
--module | Имя модуля.
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | Загрузка сервисов из контейнера.
--test | Generate a test class
