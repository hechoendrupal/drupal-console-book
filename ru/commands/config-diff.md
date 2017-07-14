# config:diff
Выводит элементы активной конфигурации, которые отличаются в сравнении с каталогом.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | Посмотреть обратные изменения (т.е. сравнение каталога с активной конфигурацией).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | Каталог для сравнения. Если не выбрано, будет выбран каталог конфигураций Drupal.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
