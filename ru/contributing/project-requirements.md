# Требования к проекту

## Загрузить Git
Мы рекомендуем загрузить Git с [http://git-scm.com/downloads](http://git-scm.com/downloads)

## Загрузить Composer

Запустите эту команду в вашей командной строке для того, чтобы получить последнюю версию Composer:
```
curl -sS https://getcomposer.org/installer | php
```
Или если у вас не установлен curl:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
Этот установочный скрипт проверит некоторые настройки php.ini, предупредит вас если они установлены не верно и скачает последнюю версию composer.phar в текущий каталог

Вы можете запустить следующую команду в командной строке для того, чтобы сделать Composer доступным повсюду в вашей системе:
```
mv composer.phar /usr/local/bin/composer
```
