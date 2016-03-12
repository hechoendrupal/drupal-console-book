# config:override
The **config:override** command Переопределить значение конфигурации в активной конфигурации.

**Использование:**
```
$ drupal config:override [arguments] 
```

## Доступные параметры
Параметр | Описание
---------|-------------
config-name | Имя конфигурации.
key | Ключ
value | Значение

## Examples
* Установить лимит флуда до 10 для модуля Contact
```
$ drupal config:override contact.settings flood.limit 10
```
