# Доступные команды Drupal Console

**Внимание:** Drupal Console команды *должны* запускаться из корневого каталога инсталляции Drupal 8.

Drupal Console команды | Подробнее
------------ | -------------
[about](about.md) | Отображает базовую информацию о Drupal Console.
[chain](chain.md) | Выполнение команды chain.
[help](help.md) | Отображение помощи по командам.
[init](init.md) | Копирование конфигурационных файлов в домашнюю папку пользователя.
[list](list.md) | Список всех доступных команд.
[server](server.md) | Запуск встроенного PHP веб-сервера.
**cache**  |
[cache:rebuild](cache-rebuild.md) | Очистка и пересборка всех кэшей сайта.
**config**  |
[config:debug](config-debug.md) | Отобразить текущую конфигурацию.
[config:edit](config-edit.md) | Редактировать указанную конфигурацию.
[config:export](config-export.md) | Экспорт текущей конфигурации.
[config:export:content:type](config-export-content-type.md) | Экспорт определенного типа материала и его полей.
[config:export:single](config-export-single.md) | Экспорт единичной конфигурации в yml файл.
[config:export:view](config-export-view.md) | Экспорт представления в YAML формат в отдельный модуль для переиспользования на других проектах.
[config:import](config-import.md) | Импорт конфигурации в текущий сайт.
[config:import:single](config-import-single.md) | Импорт единичной конфигурации.
[config:override](config-override.md) | Перезаписать значение в активной конфигурации.
**container**  |
[container:debug](container-debug.md) | Отображение текущих сервисов сайта.
**create**  |
[create:nodes](create-nodes.md) | Создание материалов с демо-содержимым для текущего Drupal 8 сайта.
[create:terms](create-terms.md) | Создание демо-терминов для текущего Drupal 8 сайта.
[create:users](create-users.md) | Создание демо-пользователей для текущего Drupal 8 сайта.
[create:vocabularies](create-vocabularies.md) | Создание демо-словарей для текущего Drupal 8 сайта.
**cron**  |
[cron:debug](cron-debug.md) | Список всех модулей, использующих cron.
[cron:execute](cron-execute.md) | Запуск cron-задач помодульно или для всех модулей.
[cron:release](cron-release.md) | Снять cron-блокировку для очередного запуска сron.
**database**  |
[database:client](database-client.md) | Запуск клиента базы данных, если это возможно.
[database:connect](database-connect.md) | Отображение соединения с базой данных.
[database:dump](database-dump.md) | Экспорт копии структуры и содержимого базы данных в файл.
[database:log:clear](database-log-clear.md) | Удаление события из таблицы DBLog, доступны фильтры.
[database:log:debug](database-log-debug.md) | Отобразить текущие события из журнала.
[database:restore](database-restore.md) | Восстановление структуры и содержимого базы данных из файла.
[database:table:debug](database-table-debug.md) | Отображение всех таблиц из указанной базы.
[database:table:drop](database-table-drop.md) | Удаление всех таблиц из указанной базы.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:command](generate-command.md) | Генерация команды для консоли.
[generate:controller](generate-controller.md) | Генерация и регистрация контроллера.
[generate:doc:dash](generate-doc-dash.md) | Генерация DrupalConsole.docset пакета для Dash.
[generate:doc:gitbook](generate-doc-gitbook.md) | Генерация документации для команд.
[generate:entity:bundle](generate-entity-bundle.md) | Генерация нового типа материала (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Генерация нового "FormBase"
[generate:form:alter](generate-form-alter.md) | Генерация имплементации hook_form_alter() или hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Генерация нового "ConfigFormBase"
[generate:module](generate-module.md) | Генерация модуля.
[generate:permissions](generate-permissions.md) | Генерация прав доступа.
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Генерация типа поля, виджета и форматтера поля.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Генерация форматтера поля.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Генерация стиля обработки изображения.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:profile](generate-profile.md) | Генерация профиля.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Генерация сервиса.
[generate:theme](generate-theme.md) | Генерация темы оформления.
**locale**  |
[locale:language:add](locale-language-add.md) | Добавить язык в список поддерживаемых вашим сайтом языков.
[locale:language:delete](locale-language-delete.md) | Удалить язык из списка поддерживаемых языков.
[locale:translation:status](locale-translation-status.md) | Список доступных обновлений переводов.
**migrate**  |
[migrate:debug](migrate-debug.md) | Отображение текущих доступных миграций.
[migrate:execute](migrate-execute.md) | Запуск доступной миграции.
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:debug](module-debug.md) | Отображение списка доступных модулей.
[module:download](module-download.md) | Скачать модуль или модули.
[module:install](module-install.md) | Установить модуль или модули.
[module:uninstall](module-uninstall.md) | Деинсталлировать модуль или модули.
**multisite**  |
[multisite:debug](multisite-debug.md) | Список всех сайтов в мультисайтинге.
**rest**  |
[rest:debug](rest-debug.md) | Display current rest resource for the application
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:debug](router-debug.md) | Displays current routes for the application
[router:rebuild](router-rebuild.md) | Rebuild routes for the application
**settings**  |
[settings:debug](settings-debug.md) | Displays current key:value on settings file.
**site**  |
[site:debug](site-debug.md) | Список всех известных локальных и удаленных сайтов.
[site:install](site-install.md) | Установить Drupal.
[site:maintenance](site-maintenance.md) | Переключить сайт в режим разработки.
[site:mode](site-mode.md) | Переключение режима быстродействия сайта (development/production)
[site:new](site-new.md) | Создание нового Drupal проект.
[site:status](site-status.md) | Просмотр текущего статуса Drupal сайта.
**state**  |
[state:debug](state-debug.md) | Show the current State keys.
[state:override](state-override.md) | Show the current State keys.
**test**  |
[test:debug](test-debug.md) | List Test Units available for the application.
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:debug](theme-debug.md) | Отображение списка доступных тем оформления.
[theme:download](theme-download.md) | Загрузка темы или тем оформления.
[theme:install](theme-install.md) | Установка темы или тем оформления.
[theme:uninstall](theme-uninstall.md) | Деинсталляция темы или тем оформления.
**translation**  |
[translation:cleanup](translation-cleanup.md) | Очистка файлов переводов.
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Сгенерировать статистику по переводам.
[translation:sync](translation-sync.md) | Синхронизация файлов переводов.
**update**  |
[update:debug](update-debug.md) | Display current updates available for the application
[update:execute](update-execute.md) | Execute a specific Update N function in a module, or execute all
**user**  |
[user:debug](user-debug.md) | Отображение списка текущих пользователей.
[user:delete](user-delete.md) | Удаление пользователей.
[user:login:clear:attempts](user-login-clear-attempts.md) | Очистка неверных попыток входа в аккаунт.
[user:login:url](user-login-url.md) | Возврат ссылки для одноразового входа.
[user:password:hash](user-password-hash.md) | Генерация хэш-ключа из введенного пароля.
[user:password:reset](user-password-reset.md) | Сброс пароля указанному пользователю.
**views**  |
[views:debug](views-debug.md) | Отобразить список доступных представлений.
[views:disable](views-disable.md) | Отключить представление.
[views:enable](views-enable.md) | Активировать представление.
**yaml**  |
[yaml:diff](yaml-diff.md) | Сравнение двух YAML файлов.
[yaml:merge](yaml-merge.md) | Слияние двух или более YAML файлов в новый YAML файл. Сохраняются последние значения.
[yaml:split](yaml-split.md) | Разделение YAML файла по указанному критерию.
[yaml:update:key](yaml-update-key.md) | Переписать YAML ключ в YAML файле.
[yaml:update:value](yaml-update-value.md) | Обновление значения указанного ключа в YAML файле.

## Доступные опции
Опция | Описание
-------|-------------
--help | Отображение данного сообщения о помощи.
--quiet | Не выводить никаких сообщений.
--verbose | Повысить информативность сообщений: 1 для обычного вывода, 2 для более подробного вывода и 3 для отладки.
--version | Отображение версии Drupal Console.
--ansi | Использование ANSI вывода.
--no-ansi | Отключение ANSI вывода.
--no-interaction | Не запрашивать подтверждений в процессе выполнения.
--env | Имя окружения.
--root | Указать корневой каталог Drupal для использования в запуске команд.
--no-debug | Выключение режима отладки.
--learning | Генерировать подробный вывод кода
--generate-chain | Отображение опций и аргументов команд в yaml для использования в последовательности (chain) команд.
--generate-inline | Отображение опций и аргументов команд как inline-команды.
--generate-doc | Отобразить опции и аргументы кманды в виде markdown.
--target | Имя сайта, с которым вы хотите взаимодействовать (для локальных или удаленных сайтов).
--uri | URI Drupal сайта для использования (для использования в мультисайтинге или для нестандартного порта).
--yes | Пропустить запрос подтверждения и продолжить выполнение команды.

## Доступные аргументы
Аргумент | Описание
---------|-------------
command | Команда для запуска
