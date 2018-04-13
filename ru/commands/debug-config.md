# debug:config
Показывает текущую конфигурацию.

**Использование:**
```
drupal debug:config [arguments] [options]
dc
```

## Доступные параметры
Команда | Детали
-------|-------------
--show-overridden | commands.debug.config.options.show-overridden

## Доступные аргументы
Аргумент | Детали
---------|-------------
name | Имя конфигурации.

## Примеры
* Отображает все имена объектов конфигурации.
```
drupal config:debug
```
* Display system site configurations values.
```
drupal config:debug system.site
```
* Выводит все имена кофигурации содержащие system.
```
drupal config:debug | grep system
```
