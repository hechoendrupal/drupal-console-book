# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | 顯示 Drupal Console 專案的基本資訊
[chain](chain.md) | Chain command execution
[check](check.md) | System requirement checker
[exec](exec.md) | Execute an external command.
[help](help.md) | Displays help for a command
[init](init.md) | 複製設定檔到使用者目錄.
[list](list.md) | Lists all available commands
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | 運行內建的 PHP 網頁伺服器
**cache**  |
[cache:rebuild](cache-rebuild.md) | 重建和清除所有快取
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Edit the selected configuration.
[config:export](config-export.md) | Export current application configuration.
[config:export:content:type](config-export-content-type.md) | Export a specific content type and their fields.
[config:export:single](config-export-single.md) | Export single configuration as yml file.
[config:export:view](config-export-view.md) | Export a view in YAML format inside a provided module to reuse in other website.
[config:import](config-import.md) | Import configuration to current application.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Override config value in active configuration.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:execute](cron-execute.md) | Execute cron implementations by module or execute all crons
[cron:release](cron-release.md) | Release cron system lock to run cron again
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Shows DB connection
[database:drop](database-drop.md) | Drop all tables in a given database.
[database:dump](database-dump.md) | Dump structure and contents of a database
[database:log:clear](database-log-clear.md) | Remove events from DBLog table, filters are available
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Restore structure and contents of a database.
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | 列出可用的連續命令檔案
[debug:config](debug-config.md) | Show the current configuration.
[debug:config:settings](debug-config-settings.md) | Displays current key:value on settings file.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Displays current services for an application.
[debug:cron](debug-cron.md) | List of modules implementing a cron
[debug:database:log](debug-database-log.md) | Display current log events for the application
[debug:database:table](debug-database-table.md) | Show all tables in a given database.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | 顯示可用的 libraries
[debug:migrate](debug-migrate.md) | Display current migration available for the application
[debug:module](debug-module.md) | Display current modules available for application
[debug:multisite](debug-multisite.md) | 列出系統中可用的多站設置
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | 顯示全部外掛模組資訊，包含外掛類型、指定類別的外掛實體，或是指定外掛的定義說明
[debug:queue](debug-queue.md) | 顯示網站應用中的排程隊列
[debug:rest](debug-rest.md) | 列出網站應用中的 REST 資源
[debug:router](debug-router.md) | 顯示目前網站應用中建立的途徑
[debug:settings](debug-settings.md) | 列出使用者的 Drupal Console 設置
[debug:site](debug-site.md) | 列出所有已知的本地端與遠端網站資訊。
[debug:state](debug-state.md) | 列出現有系統狀態鍵名
[debug:test](debug-test.md) | 列出網站應用中可用的單元測試
[debug:theme](debug-theme.md) | 顯示預設的版型
[debug:update](debug-update.md) | 顯示目前網站應用中所有可用的更新項目
[debug:user](debug-user.md) | 顯示目前網站應用中的使用者
[debug:views](debug-views.md) | 顯示目前網站應用中的 Views 資源
[debug:views:plugins](debug-views-plugins.md) | 顯示目前網站應用的 Views 外掛
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
[generate:form](generate-form.md) | Generate a new "%s"
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
[generate:service](generate-service.md) | Generate service
[generate:theme](generate-theme.md) | Generate a theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Install module or modules in the application
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | 重建內容存取權限。重建過程將移除現有權限並依照目前模組與設定取代成為新權限。
**queue**  |
[queue:run](queue-run.md) | 處理選中的排程隊列（queue）。
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | 停用網站應用中的 REST 資源
[rest:enable](rest-enable.md) | 為網站應用啟用 REST 資源
**router**  |
[router:rebuild](router-rebuild.md) | 重建網站應用途徑
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | 在 DrupalConsole 設定檔裡修改設定內容
**site**  |
[site:import:local](site-import-local.md) | 匯入或設定本地現存的 Drupal 專案
[site:install](site-install.md) | 安裝一個 Drupal 專案
[site:maintenance](site-maintenance.md) | 切換網站維護模式
[site:mode](site-mode.md) | 切換系統效能設置
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | 顯示目前網站統計資訊。
[site:status](site-status.md) | 顯示 Drupal 安裝資訊
**state**  |
[state:delete](state-delete.md) | 清除系統狀態
[state:override](state-override.md) | 覆寫系統狀態的鍵名。
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | 執行網站應用中可用的單元測試
**theme**  |
[theme:download](theme-download.md) | 下載網站版型
[theme:install](theme-install.md) | 安裝一或多個版型至網站應用中
[theme:path](theme-path.md) | 取得版型所在相關或絕對路徑
[theme:uninstall](theme-uninstall.md) | 解除安裝網站應用中，一或多個版型
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | 執行實體更新
[update:execute](update-execute.md) | 執行模組中指定編號的更新，或執行全部更新
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | 刪除網站應用中的使用者
[user:login:clear:attempts](user-login-clear-attempts.md) | 清除使用者錯誤嘗試登入記錄
[user:login:url](user-login-url.md) | 為使用者取得一次性登入網址。
[user:password:hash](user-password-hash.md) | 從純文字密碼產生雜湊值（Hash）
[user:password:reset](user-password-reset.md) | 重設指定使用者帳號的密碼。
[user:role](user-role.md) | 指派或移除使用者所屬角色
**views**  |
[views:disable](views-disable.md) | 關閉這個 View
[views:enable](views-enable.md) | 啟用這個 View

## Available options
Option | Details
-------|-------------
--help | 顯示這個幫助訊息
--quiet | 不顯示任何幫助訊息
--verbose | 輸出訊息控制: 1 普通輸出, 2 詳細輸出 and 3 除錯訊息輸出
--version | 顯示這個程式的版本
--ansi | 強制 ANSI 輸出
--no-ansi | 關閉 ANSI 輸出
--no-interaction | 不要顯示任何對話問題
--env | 環境名稱
--root | 定義 Drupal 根目錄，命令執行時使用
--debug | application.options.debug
--learning | 產生學習用的詳細代碼
--generate-chain | 以 YAML 格式顯示命令執行時的選項和參數，用於連續執行一組命令
--generate-inline | 將命令執行時的選項和參數顯示成一行，以便後續使用
--generate-doc | 顯示命令選項和參數為 markdown 格式
--target | 與它互動的網站名稱（本地或遠端網站）
--uri | Drupal 網站的 URI( 用於多網站環境或運行在不同的端口)
--yes | 跳過確認並繼續

## Available arguments
Argument | Details
---------|-------------
command | 要執行的命令
