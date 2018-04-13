# generate:authentication:provider
Генерирует провайдер аутентификации

**Использование:**
```
drupal generate:authentication:provider [options]
gap
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Класс провайдера аутентификации
--provider-id | ID провайдера

## Примеры
* Генерирует провайдер аутентификации по модулю, классу и ID  провайдера
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
