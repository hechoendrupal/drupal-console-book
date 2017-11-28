# Установка

Drupal Console это модульный проект использующий множество репозиториев.

Главные репозитории:
* [drupal/console](https://github.com/hechoendrupal/drupal-console)
* [drupal/console-core](https://github.com/hechoendrupal/drupal-console-core)
* [drupal/console-extend-plugin](https://github.com/hechoendrupal/drupal-console-extend-plugin)
* [drupal-console-dotenv](https://github.com/weknowinc/drupal-console-dotenv)

Дополнительные проекты:
* [drupal/console-develop](https://github.com/weknowinc/drupal-console-develop)
* [drupal-console-yaml](https://github.com/weknowinc/drupal-console-yaml)

Языки также разделены на отдельные репозитории:
* [drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
* [drupal-console-es](https://github.com/hechoendrupal/drupal-console-es)

## Создание fork
Вам необходимо создать fork для репозитория в который вы хотите внести свои изменения. Для это задачи вы можете использовать GitHub интерфейс.

## Клонирование
Вам необходимо указать каталог куда вы хотите склонировать репозитории, например `/Users/username/drupal-console-code`
```
cd /Users/username/drupal-console-code
git clone git@github.com:[your-github-user-here]/drupal-console.git
git clone git@github.com:[your-github-user-here]/drupal-console-core.git
git clone git@github.com:[your-github-user-here]/drupal-console-en.git
```

## Установка зависимостей
Теперь когда вы склонировали репозитории, вам необходимо скачать все зависимости используя Composer.
```
cd /Users/username/drupal-console-code/[cloned-repository]
composer install
```

Читайте следующий шаг, чтобы понять как связать и протестировать эти репозитории на вашем Drupal сайте.
