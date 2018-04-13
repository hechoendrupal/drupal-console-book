# config:override
Переопределить значение конфигурации в активной конфигурации.

**Использование:**
```
drupal config:override [arguments]
co
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
name | Имя конфигурации
key | Ключ
value | Значение

## Примеры
* Установить лимит флуда до 10 для модуля Contact
```
drupal config:override contact.settings flood.limit 10
```
