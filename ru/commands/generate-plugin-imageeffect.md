# generate:plugin:imageeffect
Генерирует плагин эффект изображения.

**Использование:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса типа плагина
--label | Заголовок плагина
--plugin-id | ID плагина
--description | Описание плагина

## Примеры
* Генерирует плагин эффект изображения по имени модуля, классу, заголовку, ID плагина и описанию
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
