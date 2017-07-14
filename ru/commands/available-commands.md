# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Отображение основных сведений о проекте Drupal Console
[chain](chain.md) | Последовательное выполнение команд
[check](check.md) | Проверка системных требований
[exec](exec.md) | Execute an external command.
[help](help.md) | Показывает справку для команды
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Списки всех доступных команд
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Перестроить и очистить весь кеш сайта.
**config**  |
[config:delete](config-delete.md) | Удалить конфигурацию
[config:diff](config-diff.md) | Выводит элементы активной конфигурации, которые отличаются в сравнении с каталогом.
[config:edit](config-edit.md) | Редактирование выбранной конфигурации.
[config:export](config-export.md) | Экспорт текущей конфигурации приложения.
[config:export:content:type](config-export-content-type.md) | Экспорт выбранного типа материала и его полей.
[config:export:single](config-export-single.md) | Экспорт конфигурации в yml файл.
[config:export:view](config-export-view.md) | Экспорт представления в YAML формат внутри модуля для повторного использования на другом сайте.
[config:import](config-import.md) | Импорт конфигурации в текущее приложение.
[config:import:single](config-import-single.md) | Импорт выбранной конфигурации.
[config:override](config-override.md) | Переопределить значение конфигурации в активной конфигурации.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**create**  |
[create:comments](create-comments.md) | Создание фиктивных комментариев для Drupal 8.
[create:nodes](create-nodes.md) | Создание фиктивных материалов для Drupal 8.
[create:terms](create-terms.md) | Создание фиктивных терминов для Drupal 8.
[create:users](create-users.md) | Создание фиктивных пользователей для Drupal 8.
[create:vocabularies](create-vocabularies.md) | Создание фиктивных словарей для Drupal 8.
**cron**  |
[cron:execute](cron-execute.md) | Выполнить cron реализацию для модуля иои выполнить все cron-задачи
[cron:release](cron-release.md) | Снимает блокировку с cron-а для повторного запуска
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Запуск клиента базы данных, если он доступен
[database:connect](database-connect.md) | Показывает соединение с базой данных
[database:drop](database-drop.md) | Удалить все таблицы в данной базе данных.
[database:dump](database-dump.md) | Дамп структуры и содержимого базы данных
[database:log:clear](database-log-clear.md) | Удалить события из таблицы DBLog, фильтры доступны
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Восстановление структуры и содержимого базы данных
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | List available chain files.
[debug:config](debug-config.md) | Показывает текущую конфигурацию.
[debug:config:settings](debug-config-settings.md) | Отображает текущий Ключ:значение в файле настроек.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Отображает текущие сервисы для приложения.
[debug:cron](debug-cron.md) | Список модулей реализующих cron
[debug:database:log](debug-database-log.md) | Показать текущий журнал событий приложения
[debug:database:table](debug-database-table.md) | Показать все таблицы в данной базе данных.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Отображение текущей миграции, доступной для приложения
[debug:module](debug-module.md) | Отображение текущих модулей доступных для приложения
[debug:multisite](debug-multisite.md) | Список всех мультисайтов доступных в системе
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Display current rest resource for the application
[debug:router](debug-router.md) | Displays current routes for the application
[debug:settings](debug-settings.md) | List user Drupal Console settings.
[debug:site](debug-site.md) | List all known local and remote sites.
[debug:state](debug-state.md) | Show the current State keys.
[debug:test](debug-test.md) | List Test Units available for the application.
[debug:theme](debug-theme.md) | Отображает текущие темы для приложения
[debug:update](debug-update.md) | Отобразить обновления доступные для приложения
[debug:user](debug-user.md) | Displays current users for the application
[debug:views](debug-views.md) | Отображение текущих ресурсов представлений приложения
[debug:views:plugins](debug-views-plugins.md) | Отображает существующие плагины Представлений для приложения
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**develop**  |
[develop:contribute](develop-contribute.md) | 
[develop:example](develop-example.md) | 
[develop:example:container:aware](develop-example-container-aware.md) | 
[develop:gitbook](develop-gitbook.md) | Update gitbook
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Delete an specific entity
**extend**  |
[extend:example:one](extend-example-one.md) | Drupal Console extend example
[extend:example:two](extend-example-two.md) | Drupal Console extend example
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | commands.generate.doc.cheatsheet.description
[generate:doc:dash](generate-doc-dash.md) | commands.generate.doc.dash.description
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | commands.generate.doc.gitbook.description
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Генерировать новую "%s"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:module](generate-module.md) | Generate a module.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Generate field type, widget and formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generate field formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generate image effect plugin.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Генерирует сервис
[generate:theme](generate-theme.md) | Generate a theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Добавить поддержку языка вашим сайтом
[locale:language:delete](locale-language-delete.md) | Удалить поддержку языка с вашего сайта
[locale:translation:status](locale-translation-status.md) | Список доступных обновлений переводов
**migrate**  |
[migrate:execute](migrate-execute.md) | Выполнить миграцию доступную для приложения
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Загрузить и создать соответствующие миграции для предоставленной устаревшой базы данных
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Скачать модуль или модули в приложение
[module:install](module-install.md) | Install module or modules in the application
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:rebuild](router-rebuild.md) | Отображает маршруты для приложения
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Install a Drupal project
[site:maintenance](site-maintenance.md) | Переключить сайт в режим обслуживания
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | Отобразить текущую статистику сайта.
[site:status](site-status.md) | View current Drupal Installation status
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Override a State key.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:download](theme-download.md) | Download theme in application
[theme:install](theme-install.md) | Установить тему или темы в приложение
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Uninstall theme or themes in the application
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Выполнить конкретный update_N хук в модуле или выполнить все
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Сброс неудачных попыток входа в аккаунт.
[user:login:url](user-login-url.md) | Возвращает одноразовый url для входа.
[user:password:hash](user-password-hash.md) | Сгенерировать хеш для пароля.
[user:password:reset](user-password-reset.md) | Сброс пароля указанного пользователя.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Отключить представление
[views:enable](views-enable.md) | Включить представление

## Available options
Option | Details
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | <info>"%s"</info> версия <comment>"%s"</comment>
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | Имя среды окружения
--root | Указать корневую директорию Drupal для выполнения команд
--debug | application.options.debug
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
command | The command to execute
