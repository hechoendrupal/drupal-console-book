# site:install
Устанавливает Drupal проект

**Использование:**
```
drupal site:install [arguments] [options]
si
```

## Доступные параметры
Команда | Детали
-------|-------------
--langcode | Язык Drupal
--db-type | Тип базы данных Drupal, которая будет установлена
--db-file | Drupal файл базы данных, которая будет установлена
--db-host | Хост базы данных
--db-name | Имя базы данных
--db-user | Пользователь базы данных
--db-pass | Пароль базы данных
--db-prefix | Префикс базы данных
--db-port | Порт базы данных
--site-name | Название сайта Drupal
--site-mail | E-mail сайта Drupal
--account-name | Имя пользователя администратора Drupal
--account-mail | E-mail администратора Drupal
--account-pass | Пароль администратора Drupal
--force | Force to reinstall the site

## Доступные аргументы
Аргумент | Детали
---------|-------------
profile | Профайл Drupal, который будет установлен

## Примеры
* Установка проекта drupal, передавая тип установки, код языка, конфигурацию базы данных, имя сайта, E-mail сайта и данные для администратора сайта
```
drupal site:install  standard  \
  --langcode="en"  \
  --db-type="mysql"  \
  --db-host="127.0.0.1"  \
  --db-name="drupal8"  \
  --db-user="u53rn4m3"  \
  --db-pass="dbp455"  \
  --db-port="3306"  \
  --site-name="Drupal 8"  \
  --site-mail="admin@example.com"  \
  --account-name="admin"  \
  --account-mail="admin@example.com"  \
  --account-pass="p455w0rd"
```
