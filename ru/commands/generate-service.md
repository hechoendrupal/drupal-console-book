# generate:service
Генерирует сервис

**Использование:**
```
drupal generate:service [options]
gs
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--name | Имя сервиса
--class | Имя класса
--interface | Интерфейс
--interface-name | Interface name
--services | Загрузка сервисов из контейнера.
--path-service | Path

## Примеры
* Генерирует сервис без интерфейса по имени модуля, имени сервиса, классу и пути
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --path-service="/modules/custom/modulename/src/"
```
* Генерирует сервис с интерфейсом по имени модуля, имени сервиса, классу и пути
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --interface  \
  --interface-name="InterfaceName"  \
  --path-service="/modules/custom/modulename/src/"
```
