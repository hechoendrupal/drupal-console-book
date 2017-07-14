# migrate:execute
Выполнить миграцию доступную для приложения

**Usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Available options
Option | Details
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
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Available arguments
Argument | Details
---------|-------------
migration-ids | Идентификатор(ы) миграции
