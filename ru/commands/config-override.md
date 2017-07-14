# config:override
Переопределить значение конфигурации в активной конфигурации.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Имя конфигурации
key | Ключ
value | Значение

## Examples
* Установить лимит флуда до 10 для модуля Contact
```
drupal config:override contact.settings flood.limit 10
```
