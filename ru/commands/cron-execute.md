# cron:execute
Выполнить cron реализацию для модуля иои выполнить все cron-задачи

**Использование:**
```
drupal cron:execute [arguments]
croe
cre
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
module | Имя модуля.

## Примеры
* Запустить cron глобально
```
drupal cron:execute
```
* Запустить cron для специфичного модуля
```
drupal cron:execute \
  <module>
```
