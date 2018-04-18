# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Drupal Consoleプロジェクトについての基本情報を表示
[chain](chain.md) | 連続した複数のコマンドを実行
[check](check.md) | 動作環境をチェックする
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | 外部コマンドを実行する
[help](help.md) | コマンドのヘルプを表示する
[init](init.md) | 設定ファイルをユーザーのホームディレクトリにコピーする
[list](list.md) | 利用可能なコマンド一覧を表示する
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | PHPのbuilt-in web serverでDrupalを起動する
**cache**  |
[cache:rebuild](cache-rebuild.md) | キャッシュのクリアと再生成
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | 設定を削除する
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | 設定を編集する
[config:export](config-export.md) | 設定をエクスポートする
[config:export:content:type](config-export-content-type.md) | コンテンツタイプとフィールドをエクスポート
[config:export:single](config-export-single.md) | 単一のコンフィグレーションをymlファイルとしてエクスポート
[config:export:view](config-export-view.md) | Export a view in YAML format inside a provided module to reuse in other website.
[config:import](config-import.md) | Import configuration to current application.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Override config value in active configuration.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | ダミーのコメントを作成
[create:nodes](create-nodes.md) | ダミーのノードを作成
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | ダミーのタームを作成
[create:users](create-users.md) | ダミーのユーザーを作成
[create:vocabularies](create-vocabularies.md) | ダミーのボキャブラリーを追加
**cron**  |
[cron:execute](cron-execute.md) | モジュール単位、もしくは全てのcronを実行
[cron:release](cron-release.md) | Cronのシステムロックを解放
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | データベースクライアントを起動
[database:connect](database-connect.md) | データベースクライアントを起動
[database:drop](database-drop.md) | データベースから全てのテーブルを削除
[database:dump](database-dump.md) | データベースの構造とコンテンツをダンプ
[database:log:clear](database-log-clear.md) | DbLogからイベントを削除する
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | データベースの構造とコンテンツをリストア
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | 利用可能なブレークポイントの一覧を表示
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | チェーンファイルの一覧を表示
[debug:config](debug-config.md) | 現在の設定を表示する
[debug:config:settings](debug-config-settings.md) | 設定ファイル内のKey-Valueペアを表示する
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | サービスを表示
[debug:cron](debug-cron.md) | cronを実装しているモジュールの一覧を表示
[debug:database:log](debug-database-log.md) | DBLogのイベントを表示
[debug:database:table](debug-database-table.md) | データベース内の全てのテーブルを表示
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | 画像スタイルの一覧を表示
[debug:libraries](debug-libraries.md) | ライブラリを表示
[debug:migrate](debug-migrate.md) | マイグレーションを表示
[debug:module](debug-module.md) | 利用可能なモジュールを表示
[debug:multisite](debug-multisite.md) | マルチサイトの一覧を表示
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | キューを表示
[debug:rest](debug-rest.md) | Restリソースを表示
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | ルートを表示
[debug:settings](debug-settings.md) | Drupal Consoleのユーザー設定を表示する
[debug:site](debug-site.md) | 全てのローカルおよびリモートサイトを表示する
[debug:state](debug-state.md) | ステートキーを表示
[debug:test](debug-test.md) | ユニットテストの一覧を表示
[debug:theme](debug-theme.md) | テーマの情報を表示
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | 利用可能なアップデートを表示
[debug:user](debug-user.md) | ユーザー情報を表示
[debug:views](debug-views.md) | Viewsのリソースを表示する
[debug:views:plugins](debug-views-plugins.md) | Viewsのプラグインを表示
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Delete an specific entity
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Generate a module.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
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
[generate:post:update](generate-post-update.md) | Generate an implementation of hook_post_update_NAME()
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Generate service
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Generate a theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | 画像スタイルのフラッシュを実行
**locale**  |
[locale:language:add](locale-language-add.md) | サイトでサポートする言語を追加
[locale:language:delete](locale-language-delete.md) | サイトでサポートする言語を削除
[locale:translation:status](locale-translation-status.md) | 利用可能な翻訳のアップデートを表示
**migrate**  |
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | モジュールをダウンロード
[module:install](module-install.md) | モジュールをインストール
[module:path](module-path.md) | モジュールの相対パスまたは絶対パスを返す
[module:uninstall](module-uninstall.md) | モジュールをアンインストール
[module:update](module-update.md) | コアやモジュールを更新
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | ノードのアクセス権限を再構築します。全てのコンテンツに対する権限設定を削除し、現在のモジュールおよび設定で置き換えます。
**queue**  |
[queue:run](queue-run.md) | 選択したキューを処理する
**rest**  |
[rest:disable](rest-disable.md) | Restリソースを無効化する
[rest:enable](rest-enable.md) | Restリソースを有効化する
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | ルートを再構築する
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Drupalプロジェクトをインストールする
[site:maintenance](site-maintenance.md) | サイトをメンテナンスモードに切り替える
[site:mode](site-mode.md) | システムのパフォーマンス設定を切り替える
[site:statistics](site-statistics.md) | サイトの統計情報を表示する
[site:status](site-status.md) | Drupalのインストール状態を表示する
**state**  |
[state:delete](state-delete.md) | ステートを削除する
[state:override](state-override.md) | ステートキーをオーバーライドする
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | ユニットテストの実行
**theme**  |
[theme:download](theme-download.md) | テーマをダウンロード
[theme:install](theme-install.md) | テーマをインストールする
[theme:path](theme-path.md) | テーマの相対パスまたは絶対パスを返す
[theme:uninstall](theme-uninstall.md) | テーマをアンインストールする
**update**  |
[update:entities](update-entities.md) | エンティティの更新を適用する
[update:execute](update-execute.md) | Update N 関数を実行する
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | ユーザーを削除
[user:login:clear:attempts](user-login-clear-attempts.md) | アカウントのログイン試行履歴をクリア
[user:login:url](user-login-url.md) | ワンタイムログインURLを生成する
[user:password:hash](user-password-hash.md) | プレーンテキストのパスワードからハッシュ値を生成
[user:password:reset](user-password-reset.md) | 指定したユーザーのパスワードをリセットする
[user:role](user-role.md) | ユーザーの役割を追加・削除する
**views**  |
[views:disable](views-disable.md) | Viewsを無効化する
[views:enable](views-enable.md) | Viewsを有効化する

## Available options
Option | Details
-------|-------------
--help | このヘルプメッセージを表示する
--quiet | コマンドからの全ての出力を抑制する
--verbose | メッセージの冗長性を上げる: 1は通常の出力、2はより冗長な出力、3はデバッグ用
--version | アプリケーションのバージョンを表示する
--ansi | ANSI出力を強制する
--no-ansi | ANSI出力を無効化する
--no-interaction | 対話的な質問を行わない
--env | 環境の名前
--root | コマンドを実行するDrupalのルートディレクトリを定義する
--debug | Switches on debug mode
--learning | 冗長なコードの出力を行う
--generate-chain | コマンドのオプションと引数をチェーンコマンドとして表示する
--generate-inline | コマンドのオプションと引数をインラインコマンドとして表示する
--generate-doc | コマンドのオプションと引数をMarkdownとして表示する
--target | サイト名 (ローカルもしくはリモートサイト向け)
--uri | DrupalサイトのURI (マルチサイトやデフォルト以外のポートを利用している場合に使用する)
--yes | 確認プロセスをスキップする

## Available arguments
Argument | Details
---------|-------------
command | 実行するコマンド
