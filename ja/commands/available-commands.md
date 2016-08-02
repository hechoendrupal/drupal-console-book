# 利用可能なDrupal Consoleのコマンド

**ノート:** Drupal Consoleのコマンドは、Drupal 8をインストールしたルートディレクトリ内で実行してください。.

Drupal Consoleのコマンド | 詳細
------------ | -------------
[about](about.md) | Drupal Consoleプロジェクトについての基本情報を表示
[chain](chain.md) | 連続した複数のコマンドを実行
[check](check.md) | 動作環境をチェックする
[help](help.md) | コマンドのヘルプを表示する
[init](init.md) | 設定ファイルをユーザーのホームディレクトリにコピーする
[list](list.md) | 利用可能なコマンド一覧を表示する
[self-update](self-update.md) | Drupal Consoleを最新バージョンに更新する
[server](server.md) | PHPのbuilt-in web serverでDrupalを起動する
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | 利用可能なブレークポイントの一覧を表示
**cache**  |
[cache:context:debug](cache-context-debug.md) | Displays current cache context for the application.
[cache:rebuild](cache-rebuild.md) | キャッシュのクリアと再生成
**chain**  |
[chain:debug](chain-debug.md) | チェーンファイルの一覧を表示
**config**  |
[config:debug](config-debug.md) | 現在の設定を表示する
[config:delete](config-delete.md) | 設定を削除する
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | 設定を編集する
[config:export](config-export.md) | 設定をエクスポートする
[config:export:content:type](config-export-content-type.md) | コンテンツタイプとフィールドをエクスポート
[config:export:view](config-export-view.md) | Export a view in YAML format inside a provided module to reuse in other website.
[config:import](config-import.md) | Import configuration to current application.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Override config value in active configuration.
[config:settings:debug](config-settings-debug.md) | 設定ファイル内のKey-Valueペアを表示する
**container**  |
[container:debug](container-debug.md) | サービスを表示
**create**  |
[create:comments](create-comments.md) | ダミーのコメントを作成
[create:nodes](create-nodes.md) | ダミーのノードを作成
[create:terms](create-terms.md) | ダミーのタームを作成
[create:users](create-users.md) | ダミーのユーザーを作成
[create:vocabularies](create-vocabularies.md) | ダミーのボキャブラリーを追加
**cron**  |
[cron:debug](cron-debug.md) | cronを実装しているモジュールの一覧を表示
[cron:execute](cron-execute.md) | モジュール単位、もしくは全てのcronを実行
[cron:release](cron-release.md) | Cronのシステムロックを解放
**database**  |
[database:client](database-client.md) | データベースクライアントを起動
[database:connect](database-connect.md) | データベースクライアントを起動
[database:drop](database-drop.md) | データベースから全てのテーブルを削除
[database:dump](database-dump.md) | データベースの構造とコンテンツをダンプ
[database:log:clear](database-log-clear.md) | DbLogからイベントを削除する
[database:log:debug](database-log-debug.md) | DBLogのイベントを表示
[database:restore](database-restore.md) | データベースの構造とコンテンツをリストア
[database:table:debug](database-table-debug.md) | データベース内の全てのテーブルを表示
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**event**  |
[event:debug](event-debug.md) | Display current events 
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | コマンドのチートシートを生成する
[generate:doc:dash](generate-doc-dash.md) | DashのためのDrupal Consoleのdocsetパッケージを生成する
[generate:doc:data](generate-doc-data.md) | コマンドのためのドキュメントを生成する
[generate:doc:gitbook](generate-doc-gitbook.md) | コマンドのためのドキュメントを生成する
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
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
[image:styles:debug](image-styles-debug.md) | 画像スタイルの一覧を表示
[image:styles:flush](image-styles-flush.md) | 画像スタイルのフラッシュを実行
**libraries**  |
[libraries:debug](libraries-debug.md) | ライブラリを表示
**locale**  |
[locale:language:add](locale-language-add.md) | サイトでサポートする言語を追加
[locale:language:delete](locale-language-delete.md) | サイトでサポートする言語を削除
[locale:translation:status](locale-translation-status.md) | 利用可能な翻訳のアップデートを表示
**migrate**  |
[migrate:debug](migrate-debug.md) | マイグレーションを表示
[migrate:execute](migrate-execute.md) | Execute a migration available for application
**module**  |
[module:debug](module-debug.md) | 利用可能なモジュールを表示
[module:download](module-download.md) | モジュールをダウンロード
[module:install](module-install.md) | モジュールをインストール
[module:path](module-path.md) | モジュールの相対パスまたは絶対パスを返す
[module:uninstall](module-uninstall.md) | モジュールをアンインストール
[module:update](module-update.md) | コアやモジュールを更新
**multisite**  |
[multisite:debug](multisite-debug.md) | マルチサイトの一覧を表示
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | ノードのアクセス権限を再構築します。全てのコンテンツに対する権限設定を削除し、現在のモジュールおよび設定で置き換えます。
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**queue**  |
[queue:debug](queue-debug.md) | キューを表示
[queue:run](queue-run.md) | 選択したキューを処理する
**rest**  |
[rest:debug](rest-debug.md) | Restリソースを表示
[rest:disable](rest-disable.md) | Restリソースを無効化する
[rest:enable](rest-enable.md) | Restリソースを有効化する
**router**  |
[router:debug](router-debug.md) | ルートを表示
[router:rebuild](router-rebuild.md) | ルートを再構築する
**settings**  |
[settings:debug](settings-debug.md) | Drupal Consoleのユーザー設定を表示する
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | 全てのローカルおよびリモートサイトを表示する
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Drupalプロジェクトをインストールする
[site:maintenance](site-maintenance.md) | サイトをメンテナンスモードに切り替える
[site:mode](site-mode.md) | システムのパフォーマンス設定を切り替える
[site:new](site-new.md) | Drupalプロジェクトを新規作成する
[site:statistics](site-statistics.md) | サイトの統計情報を表示する
[site:status](site-status.md) | Drupalのインストール状態を表示する
**state**  |
[state:debug](state-debug.md) | ステートキーを表示
[state:delete](state-delete.md) | ステートを削除する
[state:override](state-override.md) | ステートキーをオーバーライドする
**test**  |
[test:debug](test-debug.md) | ユニットテストの一覧を表示
[test:run](test-run.md) | ユニットテストの実行
**theme**  |
[theme:debug](theme-debug.md) | テーマの情報を表示
[theme:download](theme-download.md) | テーマをダウンロード
[theme:install](theme-install.md) | テーマをインストールする
[theme:path](theme-path.md) | テーマの相対パスまたは絶対パスを返す
[theme:uninstall](theme-uninstall.md) | テーマをアンインストールする
**translation**  |
[translation:cleanup](translation-cleanup.md) | 翻訳ファイルをクリーンアップする
[translation:pending](translation-pending.md) | 翻訳されていない文字列を検出する
[translation:stats](translation-stats.md) | 翻訳の統計を生成する
[translation:sync](translation-sync.md) | 翻訳ファイルを同期する
**update**  |
[update:debug](update-debug.md) | 利用可能なアップデートを表示
[update:entities](update-entities.md) | エンティティの更新を適用する
[update:execute](update-execute.md) | Update N 関数を実行する
**user**  |
[user:debug](user-debug.md) | ユーザー情報を表示
[user:delete](user-delete.md) | ユーザーを削除
[user:login:clear:attempts](user-login-clear-attempts.md) | アカウントのログイン試行履歴をクリア
[user:login:url](user-login-url.md) | ワンタイムログインURLを生成する
[user:password:hash](user-password-hash.md) | プレーンテキストのパスワードからハッシュ値を生成
[user:password:reset](user-password-reset.md) | 指定したユーザーのパスワードをリセットする
[user:role](user-role.md) | ユーザーの役割を追加・削除する
**views**  |
[views:debug](views-debug.md) | Viewsのリソースを表示する
[views:disable](views-disable.md) | Viewsを無効化する
[views:enable](views-enable.md) | Viewsを有効化する
[views:plugins:debug](views-plugins-debug.md) | Viewsのプラグインを表示
**yaml**  |
[yaml:diff](yaml-diff.md) | 2つのYAMLファイルを比較してその違いを見る。
[yaml:merge](yaml-merge.md) | 1つ以上のYAMLファイルを1つの新しいYAMLファイルにマージする。最後の値は保存される。
[yaml:split](yaml-split.md) | インデントを区切り基準に指定してYAMLファイル分割する
[yaml:update:key](yaml-update-key.md) | YAMLファイルのYAMLキーを置換する。
[yaml:update:value](yaml-update-value.md) | YAMLファイルの特定のキーの値を更新する。

## 利用可能なオプション
オプション | 詳細
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
--no-debug | デバッグモードを無効にする
--learning | 冗長なコードの出力を行う
--generate-chain | コマンドのオプションと引数をチェーンコマンドとして表示する
--generate-inline | コマンドのオプションと引数をインラインコマンドとして表示する
--generate-doc | コマンドのオプションと引数をMarkdownとして表示する
--target | サイト名 (ローカルもしくはリモートサイト向け)
--uri | DrupalサイトのURI (マルチサイトやデフォルト以外のポートを利用している場合に使用する)
--yes | 確認プロセスをスキップする

## 利用可能な引数
引数 | 詳細
---------|-------------
command | 実行するコマンド
