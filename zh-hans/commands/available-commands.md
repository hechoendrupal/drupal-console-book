# 可用的 Drupal Console 命令

**备注:** Drupal Console 命令*必须*从 Drupal 8 网站的根目录运行.

Drupal Console 命令 | 详细信息
------------ | -------------
**misc**  |
[about](about.md) | 显示有关 Drupal Console 项目的基本信息
[chain](chain.md) | 链命令执行
[check](check.md) | 系统需求检查器
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | 执行一个外部命令
[help](help.md) | 显示帮助
[init](init.md) | 拷贝配置文件到用户的 home 目录
[list](list.md) | 列出当前可用命令
[shell](shell.md) | 打开一个提供交互式REPL(Read–Eval–Print-Loop) shell.
[server](server.md) | 运行PHP内建的网站服务器
**cache**  |
[cache:rebuild](cache-rebuild.md) | 重建和清除所有网站缓存。
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | 删除配置
[config:diff](config-diff.md) | 比对目录，输出与活动配置不同的配置项。
[config:edit](config-edit.md) | 使用文本编辑器更改配置对象。
[config:export](config-export.md) | 导出当前应用配置。
[config:export:content:type](config-export-content-type.md) | 导出特定的内容类型及其字段。
[config:export:single](config-export-single.md) | 将单个配置或一系列配置导出为 yml 文件。
[config:export:view](config-export-view.md) | 在提供的模块中导出 YAML 格式的视图，以便在其他网站中重复使用。
[config:import](config-import.md) | 将配置导入当前应用程序。
[config:import:single](config-import-single.md) | 导入单个配置或一系列配置。
[config:override](config-override.md) | 覆盖活动配置中的配置值。
[config:validate](config-validate.md) | 根据其 Schema 验证 drupal 配置
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | 为您的 Drupal 8 应用程序创建评论。
[create:nodes](create-nodes.md) | 为您的 Drupal 8 应用程序创建节点。
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | 为您的 Drupal 8 应用程序创建术语。
[create:users](create-users.md) | 为您的 Drupal 8 应用程序创建用户。
[create:vocabularies](create-vocabularies.md) | 为您的 Drupal 8 应用程序创建词汇表。
**cron**  |
[cron:execute](cron-execute.md) | 执行模块实现的计划任务或执行所有计划任务
[cron:release](cron-release.md) | 释放定时任务系统锁，再次重新运行定时任务
**database**  |
[database:add](database-add.md) | 添加数据库到 settings.php
[database:client](database-client.md) | 启动数据库客户端（如果可用）
[database:connect](database-connect.md) | 显示 DB 连接
[database:drop](database-drop.md) | 删除给定数据库中的所有表。
[database:dump](database-dump.md) | 转储数据库结构和内容
[database:log:clear](database-log-clear.md) | 从 DBLog 表中删除事件，过滤器可用
[database:log:poll](database-log-poll.md) | 轮询看门狗并每 x 秒打印一次新的日志条目
[database:query](database-query.md) | 直接作为参数执行 SQL 语句
[database:restore](database-restore.md) | 还原数据库结构和内容。
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | 显示应用程序中可用的断点
[debug:cache:context](debug-cache-context.md) | 显示应用程序的当前缓存上下文。
[debug:chain](debug-chain.md) | 列出可用的链命令文件。
[debug:config](debug-config.md) | 列出配置对象名称和单个配置对象。
[debug:config:settings](debug-config-settings.md) | 显示当前设置文件的键值对。
[debug:config:validate](debug-config-validate.md) | 在安装模块之前验证 schema 实现。
[debug:container](debug-container.md) | 显示应用程序的当前服务。
[debug:cron](debug-cron.md) | 实现计划任务的模块列表
[debug:database:log](debug-database-log.md) | 显示应用程序的当前日志事件
[debug:database:table](debug-database-table.md) | 显示给定数据库中的所有表。
[debug:entity](debug-entity.md) | 调试系统中可用的实体
[debug:event](debug-event.md) | 显示当前事件 
[debug:features](debug-features.md) | 列出注册的功能。
[debug:image:styles](debug-image-styles.md) | 列出网站上的图片样式
[debug:libraries](debug-libraries.md) | 显示应用程序中可用的库
[debug:migrate](debug-migrate.md) | 显示可用于应用程序的当前迁移
[debug:module](debug-module.md) | 显示可用于应用的当前模块
[debug:multisite](debug-multisite.md) | 列出系统中可用的所有多站点
[debug:permission](debug-permission.md) | 显示所有用户权限。
[debug:plugin](debug-plugin.md) | 显示所有插件类型。
[debug:queue](debug-queue.md) | 显示应用中的队列(s)
[debug:rest](debug-rest.md) | 显示应用程序的当前 REST 资源
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | 显示应用程序的当前路由或特定路由的信息
[debug:settings](debug-settings.md) | 列出用户的 Drupal Console 设置。
[debug:site](debug-site.md) | 列出所有已知的本地和远程站点。
[debug:state](debug-state.md) | 显示当前的状态键。
[debug:test](debug-test.md) | 列出可用于应用程序的测试单元。
[debug:theme](debug-theme.md) | 显示应用程序的当前主题
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | 显示可用于应用程序的当前更新
[debug:user](debug-user.md) | 显示应用程序的当前用户
[debug:views](debug-views.md) | 显示应用程序的当前视图资源
[debug:views:plugins](debug-views-plugins.md) | 显示应用程序的当前视图插件
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
[features:import](features-import.md) | 导入模块配置
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | 生成认证提供者
[generate:breakpoint](generate-breakpoint.md) | 生成断点
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | 生成新 Console 命令
[generate:controller](generate-controller.md) | 生成并注册新控制器
[generate:entity:bundle](generate-entity-bundle.md) | 生成新内容类型（node 或实体 bundle）
[generate:entity:config](generate-entity-config.md) | 生成新配置实体
[generate:entity:content](generate-entity-content.md) | 生成新内容实体
[generate:event:subscriber](generate-event-subscriber.md) | 生成事件订阅者
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | 生成 hook_form_alter() 或 hook_form_FORM_ID_alter 实现
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | 生成 hook_help() 的一个实现
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | 生成新模块
[generate:module:file](generate-module-file.md) | 生成一个 .module 文件
[generate:permissions](generate-permissions.md) | Generate module permissions
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
[generate:post:update](generate-post-update.md) | 生成一个 hook_post_update_NAME() 的实现
[generate:profile](generate-profile.md) | 生成一个方案.
[generate:routesubscriber](generate-routesubscriber.md) | 生成一个路径订阅
[generate:service](generate-service.md) | 生成服务
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
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
[migrate:rollback](migrate-rollback.md) | 回滚一个或多个迁移
[migrate:setup](migrate-setup.md) | 导入或创建数据库迁移
**module**  |
[module:dependency:install](module-dependency-install.md) | 在应用中安装依赖模块
[module:download](module-download.md) | 下载模块
[module:install](module-install.md) | 安装模块
[module:path](module-path.md) | 返回模块的相对路径(或绝对路径)
[module:uninstall](module-uninstall.md) | 卸载模块
[module:update](module-update.md) | 更新核心,模块
**multisite**  |
[multisite:new](multisite-new.md) | 建立一个新的多站点安装文件(s)
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | 创建节点访问权限. 重建会移除所有内容上的使用权限并替换为当前模块或当前设置里的权限
**queue**  |
[queue:run](queue-run.md) | 处理选中的队列
**rest**  |
[rest:disable](rest-disable.md) | 禁用 REST 资源
[rest:enable](rest-enable.md) | 启用 REST 资源
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
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

## 可用选项
选项 | 详细信息
-------|-------------
--help | 显示此帮助消息
--quiet | 禁止命令中的所有输出
--verbose | 增加消息的冗长度：正常输出为1，更详细输出为2，调试为3
--version | 显示此应用程序版本
--ansi | 强制 ANSI 输出
--no-ansi | 禁用 ANSI 输出
--no-interaction | 不要问任何互动的问题
--env | 环境名称
--root | 定义要在命令执行中使用的 Drupal 根目录
--debug | Switches on debug mode
--learning | 生成一个详细的代码输出
--generate-chain | 将命令选项和参数显示为在 chain 命令中使用的 yaml 输出
--generate-inline | 将显示命令选项和参数作为 inline 命令
--generate-doc | 将命令选项和参数显示为 markdown
--target | 您要与之交互的网站名称（适用于本地或远程站点）
--uri | 要使用的 Drupal 站点的 URI（对于多站点环境或在备用端口上运行时）
--yes | 跳过确认并继续

## 可用参数
参数 | 详细信息
---------|-------------
command | 待执行的命令
