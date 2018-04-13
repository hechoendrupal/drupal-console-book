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
--initialize | commands.generate.command.options.initialize
--interact | commands.generate.command.options.interact
--container-aware | Команда знает о исталяции Drupal сайта, когда извлекается
--services | Загрузка сервисов из контейнера.
--generator | commands.generate.command.options.generator

## Примеры
* Генерирует команду по имени и типу расширения, классу и имени
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
