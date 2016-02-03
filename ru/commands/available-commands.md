# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
[about](about.md) | Отображение основных сведений о проекте Drupal Console
[chain](chain.md) | Последовательное выполнение команд
[help](help.md) | Displays help for a command
[settings:init](settings-init.md) | Копирование конфигурационных файлов в домашнюю директорию пользователя.
[list](list.md) | Список команд
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Перестроить и очистить весь кеш сайта.
**config**  |
[config:debug](config-debug.md) | Показывает текущую конфигурацию.
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Редактирование выбранной конфигурации.
[config:export](config-export.md) | Экспорт текущей конфигурации приложения.
[config:export:content:type](config-export-content-type.md) | Экспорт выбранного типа материала и его полей.
[config:export:single](config-export-single.md) | Экспорт конфигурации в yml файл.
[config:export:view](config-export-view.md) | Экспорт представления в YAML формат внутри модуля для повторного использования на другом сайте.
[config:import](config-import.md) | Импорт конфигурации в текущее приложение.
[config:import:single](config-import-single.md) | Импорт выбранной конфигурации.
[config:override](config-override.md) | Переопределить значение конфигурации в активной конфигурации.
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
**container**  |
[container:debug](container-debug.md) | Отображает текущие сервисы для приложения.
**create**  |
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:debug](cron-debug.md) | Список модулей реализующих крон
[cron:execute](cron-execute.md) | Выполнить реализацию крона для модуля иои выполнить все крон-задачи
[cron:release](cron-release.md) | Снимает блокировку с крона для повторного запуска
**database**  |
[database:client](database-client.md) | Запуск клиента БД, если он доступен
[database:connect](database-connect.md) | Запуск клиента БД, если он доступен
[database:dump](database-dump.md) | Дамп структуры и контента MySQL БД и таблиц
[database:log:clear](database-log-clear.md) | Удалить события из таблицы DBLog, фильтры доступны
[database:log:debug](database-log-debug.md) | Показать лог событий приложения
[database:restore](database-restore.md) | Восстановление структуры и контента MySQL БД и таблиц
[database:table:debug](database-table-debug.md) | Show all tables in a given database.
[database:table:drop](database-table-drop.md) | Drop all tables in a given database.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:dash](generate-doc-dash.md) | Generate the DrupalConsole.docset package for Dash
[generate:doc:gitbook](generate-doc-gitbook.md) | Generate documentations for Commands
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:module](generate-module.md) | Generate a module.
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Generate field type, widget and formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generate field formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generate image effect plugin.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Generate service
[generate:theme](generate-theme.md) | Generate a theme.
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | DElete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | Display current migration available for the application
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:debug](module-debug.md) | Display current modules available for application
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Install module or modules in the application
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | Список всех мультисайтов доступных в системе
**rest**  |
[rest:debug](rest-debug.md) | Display current rest resource for the application
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:debug](router-debug.md) | Displays current routes for the application
[router:rebuild](router-rebuild.md) | Rebuild routes for the application
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:init](settings-init.md) | Копирование конфигурационных файлов в домашнюю директорию пользователя.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | List all known local and remote sites.
[site:install](site-install.md) | Install a Drupal project
[site:maintenance](site-maintenance.md) | Switch site into maintenance mode
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Create a new Drupal project
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | View current Drupal Installation status
**state**  |
[state:debug](state-debug.md) | Show the current State keys.
[state:override](state-override.md) | Override a State key.
**test**  |
[test:debug](test-debug.md) | List Test Units available for the application.
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:debug](theme-debug.md) | Displays current themes for the application
[theme:download](theme-download.md) | Download theme in application
[theme:install](theme-install.md) | Install theme or themes in the application
[theme:uninstall](theme-uninstall.md) | Uninstall theme or themes in the application
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clenaup translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Отобрахить обновления доступные для приложения
[update:execute](update-execute.md) | Выполнить конкретный update_N хук в модуле или выполнить все
**user**  |
[user:debug](user-debug.md) | Displays current users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Сброс неудачных попыток входа в аккаунт.
[user:login:url](user-login-url.md) | Возвращает одноразовый url для входа.
[user:password:hash](user-password-hash.md) | Сгенерировать хеш для пароля.
[user:password:reset](user-password-reset.md) | Сброс пароля указанного пользователя.
**views**  |
[views:debug](views-debug.md) | Отображение текущих ресурсов представлений приложения
[views:disable](views-disable.md) | Отключить представление
[views:enable](views-enable.md) | Включить представление
**yaml**  |
[yaml:diff](yaml-diff.md) | Сравнение двух YAML файлов и определение различий между ними
[yaml:merge](yaml-merge.md) | Слияние одного или более YAML файлов в новый YAML файл. Последующие значения заменят собой исходные.
[yaml:split](yaml-split.md) | Разбить YAML файл используя отступ в качестве критерия разделителя
[yaml:update:key](yaml-update-key.md) | Заменить YAML ключ в YAML файле.
[yaml:update:value](yaml-update-value.md) | Обновить значение для заданного ключа в YAML файле.

## Available options
Option | Details
-------|-------------
--help | Показать эту подсказку
--quiet | Не показывать никаких сообщений
--verbose | Увеличение подробности вывода: 1 - стандартный вывод, 2 - более подробный вывод и 3 - отладочный вывод
--version | Показать версию этого приложения
--ansi | Принудительный ANSI вывод
--no-ansi | Отключить ANSI вывод
--no-interaction | Не задавать никакие интерактивные вопросы
--env | Имя среды окружения
--root | Указать корневую директорию Drupal для выполнения команд
--no-debug | Выключение режима отладки
--learning | Генерация подробного вывода
--generate-chain | Показывает парамметры и аргументы выполняемой команды как yaml вывод для передачи по цепочке
--generate-inline | Показывает парамметры и аргументы выполняемой команды одной строкой
--generate-doc | Показывает парамметры и аргументы выполняемой команды как markdown
--target | Имя сайта, с которым вы хотите взаимодействовать (для локального или удаленного сайтов)
--uri | URI сайта Drupal (в случае мультисайтингового окружения или запуска на альтернативном порту)
--yes | Пропустить подтверждение и продолжить

## Available arguments
Argument | Details
---------|-------------
command | Команда на выполнение
