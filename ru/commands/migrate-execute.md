# migrate:execute
Выполнить миграцию доступную для приложения

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--site-url | URL-адрес сайта
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Хост базы данных
--db-name | Имя базы данных
--db-user | Пользователь базы данных
--db-pass | Пароль базы данных
--db-prefix | Префикс базы данных
--db-port | Порт базы данных
--exclude | Идентификатор(ы) миграций для исключения
--source-base_path | commands.migrate.execute.options.source-base-path

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | Идентификатор(ы) миграции
