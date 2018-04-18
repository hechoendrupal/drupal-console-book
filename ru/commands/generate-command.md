# generate:command
Сгенерировать команды для консоли.

**Использование:**
```
drupal generate:command [options]
gco
```

## Доступные параметры
Команда | Детали
-------|-------------
--extension | Имя расширения.
--extension-type | Тип расширения.
--class | Имя класса, описывающего команду. (Должно оканчиваться словом 'Commmand').
--name | Имя команды.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | Команда знает о исталяции Drupal сайта, когда извлекается
--services | Загрузка сервисов из контейнера.
--generator | Add a Generator class for this command.

## Примеры
* Генерирует команду по имени и типу расширения, классу и имени
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
