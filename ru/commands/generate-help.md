# generate:help
Сгенерировать реализацию hook_help()

**Использование:**
```
drupal generate:help [options]
gh
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--description | commands.generate.help.options.description

## Примеры
* Сгенерировать hook_help(), указав имя модуля и описание
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
