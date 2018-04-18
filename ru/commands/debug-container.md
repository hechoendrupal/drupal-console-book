# debug:container
Отображает текущие сервисы для приложения.

**Использование:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Доступные параметры
Команда | Детали
-------|-------------
--parameters | Имя сервиса.
--tag | Service tag 

## Доступные аргументы
Аргумент | Детали
---------|-------------
service | Имя сервиса.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Примеры
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
