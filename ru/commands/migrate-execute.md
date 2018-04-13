# migrate:execute
Выполняет миграцию доступную для приложения

**Использование:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Доступные параметры
Команда | Детали
-------|-------------
--site-url | URL-адрес сайта
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | Хост базы данных
--db-name | Имя базы данных
--db-user | Пользователь базы данных
--db-pass | Пароль базы данных
--db-prefix | Префикс базы данных
--db-port | Порт базы данных
--exclude | Идентификатор(ы) миграций для исключения
--source-base_path | Локальный каталог содержащий код вашего сайта (например /var/www/docroot), или адрес вашего сайта (например http://example.com)

## Доступные аргументы
Аргумент | Детали
---------|-------------
migration-ids | Идентификатор(ы) миграции
