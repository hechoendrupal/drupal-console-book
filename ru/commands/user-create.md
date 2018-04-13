# user:create
Создание пользователей в приложении

**Использование:**
```
drupal user:create [arguments] [options]
uc
```

## Доступные параметры
Команда | Детали
-------|-------------
--roles | Роли пользователя
--email | Почтовый адрес пользователя
--status | Статус пользователя

## Доступные аргументы
Аргумент | Детали
---------|-------------
username | Имя нового пользователя
password | Пароль пользователя

## Примеры
* Создать активного пользователя с именем john, паролем p455w0rd, ролью authenticated и почтовым ящиком john@anexusit.com
```
drupal user:create  john p455w0rd  \
  --roles='authenticated'  \
  --email="john@anexusit.com"  \
  --status="1"
```
* Создать активного пользователя с именем doe, паролем p455w0rd, ролью administrator и почтовым ящиком doe@anexusit.com
```
drupal user:create  doe p455w0rd  \
  --roles='administrator'  \
  --email="doe@anexusit.com"  \
  --status="1"
```
