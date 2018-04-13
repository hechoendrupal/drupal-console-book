# generate:profile
Генерирует профайл.

**Использование:**
```
drupal generate:profile [options]
gpr
```

## Доступные параметры
Команда | Детали
-------|-------------
--profile | Имя профайла
--machine-name | Машинное имя (только буквы в нижнем регистре и знаки подчеркивания)
--profile-path | commands.generate.profile.options.profile-path
--description | Описание профайла
--core | Версия ядра
--dependencies | Зависимости модулей разделенные запятыми (например context, panels)
--themes | commands.generate.profile.options.themes
--distribution | Имя дистрибьюции

## Примеры
* Генерирует профайл по имени профайла, машинному имени, описанию, версии ядра и зависимостям модулей
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
