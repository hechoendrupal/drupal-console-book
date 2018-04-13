# generate:plugin:mail
Генерирует почтовый плагин

**Использование:**
```
drupal generate:plugin:mail [options]
gpm
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класса плагина
--label | Заголовок плагина
--plugin-id | ID плагина
--services | Загрузка сервисов из контейнера.

## Примеры
* Генерирует почтовый плагин по имени модуля, классу, заголовку и ID 
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
