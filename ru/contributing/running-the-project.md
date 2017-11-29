# Запуск проекта
Для того, чтобы участвовать в проекте вам необходим рабочий Drupal сайт связанный с склонированными пакетами. 

## Запуск автоматической установки
DrupalConsole предоставляет вам команду выполняющую все эти процессы установки за вас.
```
drupal develop:contribute \
--drupal=/path/to/drupal8.dev \
--code=/Users/username/drupal-console-code/
```

Опция `--drupal` указывает каталог где новый Drupal сайт будет создан и опция `--code` указывает родительский каталог куда различные DrupalConsole репозитории были склонированны.

> ПРИМЕЧАНИЕ:
>
> Вы должны сначала запустить `drupal init` для того, чтобы скопировать `~/.console/chain/develop-contribute.yml` в вашей локальной системе.
>
> Убедитесь, что у вас последняя версия DrupalConsole. Для того, чтобы получить последнюю версию DrupalConsole следуйте инструкциям [здесь](https://github.com/hechoendrupal/drupal-console-launcher/blob/master/README.md).

## Выполнение всех шагов вручную
Если вы захотите выполнить все шаги вручную, следуйте инструкциям ниже:

### Скачайте Drupal и DrupalConsole
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

### Установите Drupal, используя SQLite
```
drupal site:install standard --db-type="sqlite" --no-interaction
```
> ПРИМЕЧАНИЕ: Вы можете установить Drupal, используя MySQL, применив команду `site:install` и ответив на вопросы в интерактивном режиме или передав необходимые параметры.

### Загрузить пакет Drupal Console Develop
```
composer require drupal/console-develop --dev
```

### Создать символическую ссылку между Drupal и ответвленным репозиторием.
```
drupal develop:create:symlinks \
--code-directory=/Users/username/drupal-console-code/
```

## Загрузить дополнительные языки или пакеты Drupal Console

Если вы хотите помочь перевести Drupal Console на [Испанский](https://github.com/hechoendrupal/drupal-console-es) вам следует:

1.- Скачайте его в ваш Drupal сайт с помощью команды.

```
composer require drupal/console-es
```

2.- Создайте fork и склонируйте репозиторий в ваш локальный каталог.

3.- Выполните снова команду `develop:create:symlinks`, чтобы создать символические ссылки, включая недавно добавленные пакеты.

Это применимо к дополнительным языкам и пакеты, например [drupal/console-yaml](https://github.com/weknowinc/drupal-console-yaml).

## Заключение

Теперь вы можете делать необходимые изменения и начать помогать, делать комиты ваших изменений, отправлять ваш код в ответвленные репозитории и создавать Pull request в соответствующие репозиторий.

Приятного кодирования ... спасибо, за ваш вклад в Drupal Console.
