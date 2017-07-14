# generate:controller
Generate & Register a controller

**application.gitbook.messages.usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Имя модуля.
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | Загрузка сервисов из контейнера.
--test | Generate a test class
