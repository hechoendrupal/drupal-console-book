# config:diff
Выводит элементы активной конфигурации, которые отличаются в сравнении с каталогом.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | Посмотреть обратные изменения (т.е. сравнение каталога с активной конфигурацией).

## Available arguments
Argument | Details
---------|-------------
directory | Каталог для сравнения. Если не выбрано, будет выбран каталог конфигураций Drupal.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
