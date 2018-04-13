# generate:module
Сгенерировать модуль.

**Использование:**
```
drupal generate:module [options]
gm
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Название модуля
--machine-name | Машинное имя (только буквы в нижнем регистре и знак подчеркивания)
--module-path | Путь до модуля
--description | Описание модуля
--core | Версия ядра
--package | Module package
--module-file | Добавить файл .module
--features-bundle | Определить модуль как feature, используя предоставленное имя бандла
--composer | Добавить файл composer.json
--dependencies | Зависимости модуля через запятую (например, context, panels)
--test | Сгенерировать класс тестов
--twigtemplate | Сгенерировать шаблон темы

## Примеры
* Генерировать модуль по имени модуля, машинному имени, пути, описанию, версии ядра и имени пакета. В этом примере Composer файл, файл юнит-тестов и twig темплейт тоже будут сгенерированы
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
