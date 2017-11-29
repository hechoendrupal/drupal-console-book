# Как загрузить, установить и запустить Drupal 8

Самый простой способ попробовать Drupal 8 на вашем компьютере это запустить команду `quick:start`.

```
drupal quick:start
```
> Примечание: Сначала вы должны выполнить `drupal init`, чтобы скопировать `~/.console/chain/quick-start.yml` в вашей локальной системе.

Команда `chain` помогает вам автоматизировать извлечение команд, позволяет вам определить внешний YAML файл содержащий определение, опции и аргументы нескольких команд и запустить список этих команд в порядке определенном в файле.

Содержимое приведенного `~/.console/chain/quick-start.yml` файла:
```
# Как использовать
# quick:start --directory="/path/to/drupal-project/"
# quick:start --directory="/path/to/drupal-project/" --profile="minimal"
# quick:start --repository="acquia/lightning-project:^8.1" --directory="/path/to/drupal-project/" --profile="lightning"
command:
  name: quick:start
  description: 'Download, install and serve a new Drupal project'
vars:
  repository:
    - drupal-composer/drupal-project:8.x-dev
    - acquia/lightning-project
    - acquia/reservoir-project
  profile: standard
commands:
  # Создать Drupal проект используя DrupalComposer
  - command: exec
    arguments:
      bin: composer create-project %{{repository}} %{{directory}} --prefer-dist --no-progress --no-interaction
  # Установить Drupal
  - command: exec
    arguments:
      bin: drupal site:install %{{profile}} --root=%{{directory}} --db-type="sqlite" --no-interaction
  # Запустить встроенный PHP сервер
  - command: exec
    arguments:
      bin: drupal server --root=%{{directory}}ß
```

Конфигурация представленная выше запустит несколько команд, в этом случае команды, которые скачают и установят Drupal, используя SQLite, и в итоге запустят встроенный PHP сервер, теперь вам надо только запустить браузер и ввести 127.0.0.1:8088.

Вы можете скопировать или сделать изменения в приведенных YAML файлах, чтобы добавить команды для скачивания модулей `module:download`, для установки модулей `module:install`, импорта конфигурации `config:import` и для восстановления базы данных `database:restore` или любой другой команды представленной DrupalConsole или команды из вашего собственного модуля.
