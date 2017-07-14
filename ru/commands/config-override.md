# config:override
Переопределить значение конфигурации в активной конфигурации.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Имя конфигурации
key | Ключ
value | Значение

## application.gitbook.messages.examples
* Установить лимит флуда до 10 для модуля Contact
```
drupal config:override contact.settings flood.limit 10
```
