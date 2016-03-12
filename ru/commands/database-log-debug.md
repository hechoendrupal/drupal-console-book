# database:log:debug
The **database:log:debug** command Показать лог событий приложения

**Использование:**
```
$ drupal database:log:debug [arguments] [options] 
```

## Доступные опции
Опция | Описание
-------|-------------
--type | Фильтрация событий по типу
--severity | Фильтрация событий по уровню важности
--user-id | Фильтрация событий по ID пользователя
--reverse | Reverse the order of events
--limit | Ограничить кол-во результатов заданным числом
--offset | Смещение стартовой позиции

## Доступные параметры
Параметр | Описание
---------|-------------
event-id | ID события в DBLog
