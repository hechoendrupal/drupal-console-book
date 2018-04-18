# Список команд Drupal Console

**Внимание:** Команды Drupal Console *должны* запускаться в папке с Drupal 8.

Команда Drupal Console | Детали
------------ | -------------
**misc**  |
[about](about.md) | Отображение основных сведений о проекте Drupal Console
[chain](chain.md) | Последовательное выполнение команд
[check](check.md) | Проверка системных требований
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Выполнить внешнюю команду.
[help](help.md) | Показывает справку для команды
[init](init.md) | Копирует конфигурационные файлы в домашний каталог пользователя.
[list](list.md) | Списки всех доступных команд
[shell](shell.md) | Открывает оболочку предоставляющую интерактивный REPL (цикл-чтение-вычисление-вывод).
[server](server.md) | Запускает встроенный PHP вебсервер
**cache**  |
[cache:rebuild](cache-rebuild.md) | Перестроить и очистить весь кеш сайта.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
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
[config:validate](config-validate.md) | Валидирует Drupal конфигурацию на основе его схемы
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | Создание фиктивных комментариев для Drupal 8.
[create:nodes](create-nodes.md) | Создание фиктивных материалов для Drupal 8.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | Создание фиктивных терминов для Drupal 8.
[create:users](create-users.md) | Создание фиктивных пользователей для Drupal 8.
[create:vocabularies](create-vocabularies.md) | Создание фиктивных словарей для Drupal 8.
**cron**  |
[cron:execute](cron-execute.md) | Выполнить cron реализацию для модуля иои выполнить все cron-задачи
[cron:release](cron-release.md) | Снимает блокировку с cron-а для повторного запуска
**database**  |
[database:add](database-add.md) | Добавить базу данных в settings.php
[database:client](database-client.md) | Запуск клиента базы данных, если он доступен
[database:connect](database-connect.md) | Показывает соединение с базой данных
[database:drop](database-drop.md) | Удалить все таблицы в данной базе данных.
[database:dump](database-dump.md) | Дамп структуры и содержимого базы данных
[database:log:clear](database-log-clear.md) | Удалить события из таблицы DBLog, фильтры доступны
[database:log:poll](database-log-poll.md) | Опрашивает watchdog и распечатывает новые записи в логе каждые x секунд
[database:query](database-query.md) | Выполняет SQL выражение, напрямую из аргумента
[database:restore](database-restore.md) | Восстановление структуры и содержимого базы данных
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Отображает брейкпоинты досутпные в приложении
[debug:cache:context](debug-cache-context.md) | Отображает текущий кеш контекст для приложения.
[debug:chain](debug-chain.md) | Список доступных chain файлов.
[debug:config](debug-config.md) | Показывает текущую конфигурацию.
[debug:config:settings](debug-config-settings.md) | Отображает текущий Ключ:значение в файле настроек.
[debug:config:validate](debug-config-validate.md) | Валидирует схему имплементации перед установкой модуля.
[debug:container](debug-container.md) | Отображает текущие сервисы для приложения.
[debug:cron](debug-cron.md) | Список модулей реализующих cron
[debug:database:log](debug-database-log.md) | Показать текущий журнал событий приложения
[debug:database:table](debug-database-table.md) | Показать все таблицы в данной базе данных.
[debug:entity](debug-entity.md) | Отладка сущностей, имеющихся в системе
[debug:event](debug-event.md) | Показать текущие события
[debug:features](debug-features.md) | Отображает зарегистрированные features.
[debug:image:styles](debug-image-styles.md) | Вывести список стилей изображений на сайте
[debug:libraries](debug-libraries.md) | Выводит библиотеки, доступные в приложении
[debug:migrate](debug-migrate.md) | Отображение текущей миграции, доступной для приложения
[debug:module](debug-module.md) | Отображение текущих модулей доступных для приложения
[debug:multisite](debug-multisite.md) | Список всех мультисайтов доступных в системе
[debug:permission](debug-permission.md) | Показывает все права пользователей.
[debug:plugin](debug-plugin.md) | Отображает все типы плагинов, инстанции плагинов специфичного типа или определение специфичного плагина.
[debug:queue](debug-queue.md) | Показать очереди вашего приложения
[debug:rest](debug-rest.md) | Отображает текущие rest ресурсы для приложения
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | Отображает текущие маршруты для приложения
[debug:settings](debug-settings.md) | Вывести пользовательские настройки Drupal Console.
[debug:site](debug-site.md) | Вывести список всех заданных локальных и удаленных сайтов.
[debug:state](debug-state.md) | Показывает ключи текущего Состояния.
[debug:test](debug-test.md) | Отображает список доступных юнит тестов для приложения.
[debug:theme](debug-theme.md) | Отображает текущие темы для приложения
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | Отобразить обновления доступные для приложения
[debug:user](debug-user.md) | Выводит актуальных пользователей для приложения
[debug:views](debug-views.md) | Отображение текущих ресурсов представлений приложения
[debug:views:plugins](debug-views-plugins.md) | Отображает существующие плагины Представлений для приложения
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Удалить конкретную сущность
**features**  |
[features:import](features-import.md) | Импортирует конфигурацию модуля.
**field**  |
[field:info](field-info.md) | Просмотреть информацию о полях.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | Генерирует провайдер аутентификации
[generate:breakpoint](generate-breakpoint.md) | Генерирует брейкпоинт
[generate:cache:context](generate-cache-context.md) | Генерирует контекст кеша
[generate:command](generate-command.md) | Сгенерировать команды для консоли.
[generate:controller](generate-controller.md) | Генерирует и регистрирует контроллер
[generate:entity:bundle](generate-entity-bundle.md) | Сгенерировать новый тип контента (бандл ноды / сущности)
[generate:entity:config](generate-entity-config.md) | Генерирует сущность конфигурации
[generate:entity:content](generate-entity-content.md) | Генерирует новую контент сущность
[generate:event:subscriber](generate-event-subscriber.md) | Генерирует подписчик на событие
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Сгенерировать реализацию hook_form_alter() или hook_form_FORM_ID_alter()
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Сгенерировать реализацию hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Сгенерировать модуль.
[generate:module:file](generate-module-file.md) | Сгенерировать файл .module
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Генерирует плагин блока
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Генерирует плагин условия.
[generate:plugin:field](generate-plugin-field.md) | Генерирует плагины типа поля, виджета и форматтера
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Генерирует плагин форматтера поля.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Генерирует плагин типа поля.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Генерирует плагин виджета поля.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Генерирует плагин эффект изображения.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Генерирует плагин форматер изображения.
[generate:plugin:mail](generate-plugin-mail.md) | Генерирует почтовый плагин
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Генерирует плагин обработки для миграции
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Генерирует плагин ресурса миграции
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Генерирует плагин rest ресурса
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Генерирует плагин действия правил
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Генерирует имплементацию skeleton плагина для тех плагинов для которых Drupal Console не имеет специального генератора
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Генерирует тип плагина с обнаружением по аннотации
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Генерирует тип плагина с Yaml обнаружением
[generate:plugin:views:field](generate-plugin-views-field.md) | Генерирует плагин поля представления.
[generate:post:update](generate-post-update.md) | Генерирует имплементацию hook_post_update_NAME()
[generate:profile](generate-profile.md) | Генерирует профайл.
[generate:routesubscriber](generate-routesubscriber.md) | Генерирует RouteSubscriber
[generate:service](generate-service.md) | Генерирует сервис
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Генерирует тему.
[generate:twig:extension](generate-twig-extension.md) | Генерирует Twig расширение.
[generate:update](generate-update.md) | Генерирует имплементацию hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Отчищает кеш по стилю изображений или отчищает кеш для всех стилей изображений
**locale**  |
[locale:language:add](locale-language-add.md) | Добавить поддержку языка вашим сайтом
[locale:language:delete](locale-language-delete.md) | Удалить поддержку языка с вашего сайта
[locale:translation:status](locale-translation-status.md) | Список доступных обновлений переводов
**migrate**  |
[migrate:execute](migrate-execute.md) | Выполняет миграцию доступную для приложения
[migrate:rollback](migrate-rollback.md) | Откатывает изменения для одной или множества миграций
[migrate:setup](migrate-setup.md) | Загрузить и создать соответствующие миграции для предоставленной устаревшой базы данных
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | Скачать модуль или модули в приложение
[module:install](module-install.md) | Устанавливает модуль или модули в приложении
[module:path](module-path.md) | Возвращает относительный или абсолютный путь к модулю
[module:uninstall](module-uninstall.md) | Удаляет модуль или модули из приложения
[module:update](module-update.md) | Обновляет ядро, модуль или модули в приложении
**multisite**  |
[multisite:new](multisite-new.md) | Настраивает файлы для мультисайт установки.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Перестравает права доступа к нодам. Перестройка прав удалит все привлегии к контенту и заменит их правами основанными на текущих модулях и настройках
**queue**  |
[queue:run](queue-run.md) | Выполнить выбранную очередь.
**rest**  |
[rest:disable](rest-disable.md) | Деактивирует rest ресурсы для приложения
[rest:enable](rest-enable.md) | Активирует rest ресурсы для приложения
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | Отображает маршруты для приложения
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Меняет значение для специфичной настройки в DrupalConsole файле настроек
**site**  |
[site:import:local](site-import-local.md) | Импортирует/Конфигурирует существующий локальный Drupal проект
[site:install](site-install.md) | Устанавливает Drupal проект
[site:maintenance](site-maintenance.md) | Переключить сайт в режим обслуживания
[site:mode](site-mode.md) | Переключание конфигурацию производительности системы
[site:statistics](site-statistics.md) | Отобразить текущую статистику сайта.
[site:status](site-status.md) | Просмотр статуса текущей установки Drupal
**state**  |
[state:delete](state-delete.md) | Удаляет состояние
[state:override](state-override.md) | Перезаписывает значение состояния по ключу.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Удаляет элементы из словаря
**test**  |
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:download](theme-download.md) | Скачать тему для приложения
[theme:install](theme-install.md) | Установить тему или темы для приложения
[theme:path](theme-path.md) | Относительный путь к теме (или абсолютный)
[theme:uninstall](theme-uninstall.md) | Деинсталяция тем в прилодении
**update**  |
[update:entities](update-entities.md) | Выполняется обновление сущностей
[update:execute](update-execute.md) | Выполнить указанный update_N хук в модуле или выполнить все
**user**  |
[user:create](user-create.md) | Создание пользователей в приложении
[user:delete](user-delete.md) | Удалить пользователей из приложения
[user:login:clear:attempts](user-login-clear-attempts.md) | Сброс неудачных попыток входа в аккаунт.
[user:login:url](user-login-url.md) | Генерирует одноразовую ссылку для входа.
[user:password:hash](user-password-hash.md) | Сгенерировать хеш для пароля.
[user:password:reset](user-password-reset.md) | Сброс пароля указанного пользователя.
[user:role](user-role.md) | Добавить/отнять пользовательскую роль
**views**  |
[views:disable](views-disable.md) | Отключить представление
[views:enable](views-enable.md) | Включить представление

## Доступные параметры
Команда | Детали
-------|-------------
--help | Показать дополнительное сообщение
--quiet | Не показывать сообщений
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | <info>"%s"</info> версия <comment>"%s"</comment>
--ansi | Сообщения в формате ANSI
--no-ansi | Отключить формат ANSI для сообщений
--no-interaction | Не задавать вопросы
--env | Имя среды окружения
--root | Указать корневую директорию Drupal для выполнения команд
--debug | Switches on debug mode
--learning | Генерация подробного вывода
--generate-chain | Показать параметры и аргументы выполняемой команды как yaml вывод для передачи по цепочке
--generate-inline | Показать параметры и аргументы выполняемой команды одной строкой
--generate-doc | Показать параметры и аргументы выполняемой команды в формате markdown
--target | Имя сайта, с которым вы хотите взаимодействовать (для локального или удаленного сайтов)
--uri | URI сайта Drupal (используется для Drupal в формате мультисайта или запуска на альтернативном порту)
--yes | Пропустить подтверждение и продолжить

## Доступные аргументы
Аргумент | Детали
---------|-------------
command | Используйте команду
