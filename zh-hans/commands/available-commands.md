# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | 显示 Drupal Console 项目基本信息
[chain](chain.md) | 链式执行一组命令
[check](check.md) | 系统需求检测器
[exec](exec.md) | 执行一个外部命令
[help](help.md) | 显示帮助
[init](init.md) | 拷贝配置文件到用户的 home 目录
[list](list.md) | 列出当前可用命令
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | 运行PHP内建的网站服务器
**cache**  |
[cache:rebuild](cache-rebuild.md) | 重建缓存
**config**  |
[config:delete](config-delete.md) | 删除配置
[config:diff](config-diff.md) | 输出选取目录中和使用中不同的配置项目.
[config:edit](config-edit.md) | 编辑配置
[config:export](config-export.md) | 导出配置
[config:export:content:type](config-export-content-type.md) | 导出内容类型及其字段
[config:export:single](config-export-single.md) | 导出单个配置
[config:export:view](config-export-view.md) | 导出视图
[config:import](config-import.md) | 导入配置
[config:import:single](config-import-single.md) | 导入选择的配置
[config:override](config-override.md) | 覆写活动配置
[config:validate](config-validate.md) | Validate a drupal config against its schema
**create**  |
[create:comments](create-comments.md) | 创建评论
[create:nodes](create-nodes.md) | 生成节点
[create:terms](create-terms.md) | 生成分类术语
[create:users](create-users.md) | 生成用户
[create:vocabularies](create-vocabularies.md) | 生成词汇表
**cron**  |
[cron:execute](cron-execute.md) | 执行模块中的或所有的定时任务（cron）
[cron:release](cron-release.md) | 释放定时任务锁
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | 运行数据库客户端
[database:connect](database-connect.md) | 如果有数据库客户端，启动它
[database:drop](database-drop.md) | 删除数据库所有表
[database:dump](database-dump.md) | 导出数据库
[database:log:clear](database-log-clear.md) | 清除事件日志
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | 还原数据库
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | 显示可用的断点
[debug:cache:context](debug-cache-context.md) | 为应用显示当前缓存上下文
[debug:chain](debug-chain.md) | 列出可用链式命令文件
[debug:config](debug-config.md) | 显示当前配置
[debug:config:settings](debug-config-settings.md) | 配置文件调试
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | 显示当前服务
[debug:cron](debug-cron.md) | 列出实现定时任务的模块
[debug:database:log](debug-database-log.md) | 显示网站日志事件(s)
[debug:database:table](debug-database-table.md) | 显示数据库所有表
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | 显示当前事件
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | 列出网站的图像样式
[debug:libraries](debug-libraries.md) | 显示应用中可用的 Libraries
[debug:migrate](debug-migrate.md) | 显示当前可用迁移
[debug:module](debug-module.md) | 显示当前可用模块
[debug:multisite](debug-multisite.md) | 列出所有可用多站点
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | 显示所有插件类型,指定类型的插件实例,或指定插件的定义
[debug:queue](debug-queue.md) | 显示应用中的队列(s)
[debug:rest](debug-rest.md) | 显示当前 REST 资源
[debug:router](debug-router.md) | 显示路由
[debug:settings](debug-settings.md) | 列出用户Drupal控制台设置.
[debug:site](debug-site.md) | 列出已知当地和远程网站.
[debug:state](debug-state.md) | 显示当前状态的键(s)
[debug:test](debug-test.md) | 列出可用的程序测试.
[debug:theme](debug-theme.md) | 显示当前主题
[debug:update](debug-update.md) | 显示目前有的程序更新
[debug:user](debug-user.md) | 显示网站的当前用户(s)
[debug:views](debug-views.md) | 显示网站当前视图资源
[debug:views:plugins](debug-views-plugins.md) | 显示当前应用的视图插件
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
[generate:authentication:provider](generate-authentication-provider.md) | 生成认证提供者
[generate:breakpoint](generate-breakpoint.md) | 生成断点
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | 生成新 Console 命令
[generate:controller](generate-controller.md) | 生成并注册新控制器
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | commands.generate.doc.cheatsheet.description
[generate:doc:dash](generate-doc-dash.md) | commands.generate.doc.dash.description
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | commands.generate.doc.gitbook.description
[generate:entity:bundle](generate-entity-bundle.md) | 生成新内容类型（node 或实体 bundle）
[generate:entity:config](generate-entity-config.md) | 生成新配置实体
[generate:entity:content](generate-entity-content.md) | 生成新内容实体
[generate:event:subscriber](generate-event-subscriber.md) | 生成事件订阅者
[generate:form](generate-form.md) | 生成新 "%s"
[generate:form:alter](generate-form-alter.md) | 生成 hook_form_alter() 或 hook_form_FORM_ID_alter 实现
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | 生成 hook_help() 的一个实现
[generate:module](generate-module.md) | 生成新模块
[generate:module:file](generate-module-file.md) | 生成一个 .module 文件
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | 生成区块插件
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | 生成 CKEditor 按钮插件
[generate:plugin:condition](generate-plugin-condition.md) | 生成条件插件
[generate:plugin:field](generate-plugin-field.md) | 生成字段类型、Widget和格式化器的插件
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | 生成字段格式化器插件
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | 生成字段类型插件
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | 生成字段 Widget 插件
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | 生成图像效果插件
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | 生成图像显示插件.
[generate:plugin:mail](generate-plugin-mail.md) | 生成 mail 插件
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | 生成 REST资源插件
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | 生成一个规则（Rule）行为（action）插件
[generate:plugin:skeleton](generate-plugin-skeleton.md) | 为没有特定生成器的生成一个基本插件的实现
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | 生成一个有识别注解能力的插件类别
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | 生成一个有识别Yaml能力的插件类别
[generate:plugin:views:field](generate-plugin-views-field.md) | 生成一个定制的插件视窗域.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | 生成一个方案.
[generate:routesubscriber](generate-routesubscriber.md) | 生成一个路径订阅
[generate:service](generate-service.md) | 生成服务
[generate:theme](generate-theme.md) | 生成一个外观主题.
[generate:twig:extension](generate-twig-extension.md) | 生成一个 Twig 扩展
[generate:update](generate-update.md) | 生成一个 hook_update_N() 的实现
**image**  |
[image:styles:flush](image-styles-flush.md) | 按图像样式执行 flush 函数或对所有图像样式执行 flush 函数
**locale**  |
[locale:language:add](locale-language-add.md) | 添加一种语言
[locale:language:delete](locale-language-delete.md) | 删除一种语言
[locale:translation:status](locale-translation-status.md) | 列出可用翻译更新
**migrate**  |
[migrate:execute](migrate-execute.md) | 执行可用迁移
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | 导入或创建数据库迁移
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | 下载模块
[module:install](module-install.md) | 安装模块
[module:path](module-path.md) | 返回模块的相对路径(或绝对路径)
[module:uninstall](module-uninstall.md) | 卸载模块
[module:update](module-update.md) | 更新核心,模块
**multisite**  |
[multisite:new](multisite-new.md) | 建立一个新的多站点安装文件(s)
**node**  |
[node:access:rebuild](node-access-rebuild.md) | 创建节点访问权限. 重建会移除所有内容上的使用权限并替换为当前模块或当前设置里的权限
**queue**  |
[queue:run](queue-run.md) | 处理选中的队列
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | 禁用 REST 资源
[rest:enable](rest-enable.md) | 启用 REST 资源
**router**  |
[router:rebuild](router-rebuild.md) | 重建路由
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | 改变 DrupalConsole 配置文件中的配置
**site**  |
[site:import:local](site-import-local.md) | 导入/配置一个已经存在的 Drupal 项目
[site:install](site-install.md) | 安装 Drupal
[site:maintenance](site-maintenance.md) | 切换网站到维护模式
[site:mode](site-mode.md) | 转换系统性能配置
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | 显示网站的当前统计
[site:status](site-status.md) | 当前Drupal安装状态
**state**  |
[state:delete](state-delete.md) | 删除状态
[state:override](state-override.md) | 覆写状态键的值
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | 运行这个程序有的测试单元
**theme**  |
[theme:download](theme-download.md) | 下载主题
[theme:install](theme-install.md) | 安装主题
[theme:path](theme-path.md) | 返回主题的相对路径 (或绝对路径)
[theme:uninstall](theme-uninstall.md) | 卸载程序的一个或多个外观主题
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | 应用实体更新
[update:execute](update-execute.md) | 执行的给出的某个模块的更新程序或者执行所有的更新程序
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | 删除网站用户(s)
[user:login:clear:attempts](user-login-clear-attempts.md) | 清空一个用户的登录尝试数据。
[user:login:url](user-login-url.md) | 返回一次性登录链接.
[user:password:hash](user-password-hash.md) | 从文本格式密码中生成哈希码
[user:password:reset](user-password-reset.md) | 为指定用户重设密码.
[user:role](user-role.md) | 添加/移除给定用户的角色
**views**  |
[views:disable](views-disable.md) | 停启视图
[views:enable](views-enable.md) | 启用一个视图

## Available options
Option | Details
-------|-------------
--help | 显示这个帮助信息
--quiet | 不显示任何帮助信息
--verbose | 输出信息控制: 1 普通输出, 2 详细输出 and 3 调试信息输出
--version | <info>"%s"</info> 版本 <comment>"%s"</comment>
--ansi | 强制 ANSI 输出
--no-ansi | 禁用 ANSI 输出
--no-interaction | 非交互式
--env | 环境名称
--root | 定义 Drupal 根目录，命令执行时使用
--debug | application.options.debug
--learning | 生成详细的代码输出用于学习
--generate-chain | 以 YAML 格式显示命令执行时的选项和参数，用于链式执行一组命令
--generate-inline | 将命令执行时的选项和参数显示成一行，以便后续使用
--generate-doc | 显示命令选项和参数为 markdown 格式
--target | 与之交互的站点名字（本地或远程网站）
--uri | Drupal 网站的 URI( 用于多站点环境或运行在不同的端口)
--yes | 跳过确认并继续

## Available arguments
Argument | Details
---------|-------------
command | 要执行的命令
