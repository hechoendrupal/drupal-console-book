# 可用 Drupal Console 命令

**备注:** Drupal Console 命令*必须*在 Drupal 8 安装目录里运行.

Drupal Console 命令 | 详细
------------ | -------------
[about](about.md) | 显示 Drupal Console 项目基本信息
[chain](chain.md) | 链式执行一组命令
[check](check.md) | commands.check.description
[help](help.md) | 显示帮助
[init](init.md) | commands.init.description
[list](list.md) | 列出当前可用命令
[self-update](self-update.md) | 更新项目到最新版本
[server](server.md) | 运行PHP内建的网站服务器
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | commands.breakpoints.debug.description
**cache**  |
[cache:rebuild](cache-rebuild.md) | 重建缓存
**chain**  |
[chain:debug](chain-debug.md) | 列出可用链式命令文件
**config**  |
[config:debug](config-debug.md) | 显示当前配置
[config:delete](config-delete.md) | 删除配置
[config:diff](config-diff.md) | 输出选取目录中和使用中不同的配置项目.
[config:edit](config-edit.md) | 编辑配置
[config:export](config-export.md) | 导出配置
[config:export:content:type](config-export-content-type.md) | 导出内容类型及其字段
[config:export:single](config-export-single.md) | 导出单个配置
[config:export:view](config-export-view.md) | 导出视图
[config:import](config-import.md) | 导入配置
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | 覆写活动配置
[config:settings:debug](config-settings-debug.md) | 配置文件调试
**container**  |
[container:debug](container-debug.md) | 显示当前服务
**create**  |
[create:comments](create-comments.md) | 创建评论
[create:nodes](create-nodes.md) | 生成节点
[create:terms](create-terms.md) | 生成分类术语
[create:users](create-users.md) | 生成用户
[create:vocabularies](create-vocabularies.md) | 生成词汇表
**cron**  |
[cron:debug](cron-debug.md) | 列出实现定时任务的模块
[cron:execute](cron-execute.md) | 执行模块中的或所有的定时任务（cron）
[cron:release](cron-release.md) | 释放定时任务锁
**database**  |
[database:client](database-client.md) | 运行数据库客户端
[database:connect](database-connect.md) | 如果有数据库客户端，启动它
[database:drop](database-drop.md) | 删除数据库所有表
[database:dump](database-dump.md) | 导出数据库
[database:log:clear](database-log-clear.md) | 清除事件日志
[database:log:debug](database-log-debug.md) | 显示网站日志事件(s)
[database:restore](database-restore.md) | 还原数据库
[database:table:debug](database-table-debug.md) | 显示数据库所有表
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | 生成认证提供者
[generate:command](generate-command.md) | 生成新 Console 命令
[generate:controller](generate-controller.md) | 生成并注册新控制器
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | 生成 Dash 文档
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | 生成命令文档
[generate:entity:bundle](generate-entity-bundle.md) | 生成新内容类型（node 或实体 bundle）
[generate:entity:config](generate-entity-config.md) | 生成新配置实体
[generate:entity:content](generate-entity-content.md) | 生成新内容实体
[generate:event:subscriber](generate-event-subscriber.md) | 生成事件订阅者
[generate:form](generate-form.md) | 生成新 "FormBase"
[generate:form:alter](generate-form-alter.md) | 生成 hook_form_alter() 或 hook_form_FORM_ID_alter 实现
[generate:form:config](generate-form-config.md) | 生成新 "ConfigFormBase"
[generate:module](generate-module.md) | 生成新模块
[generate:permissions](generate-permissions.md) | 生成模块权限
[generate:plugin:block](generate-plugin-block.md) | 生成区块插件
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | 生成条件插件
[generate:plugin:field](generate-plugin-field.md) | 生成字段类型、Widget和格式化器的插件
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | 生成字段格式化器插件
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | 生成字段类型插件
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | 生成字段 Widget 插件
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | 生成图像效果插件
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | 生成图像显示插件.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | 生成 REST资源插件
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | 生成一个插件的规则（Rule）行为（action）
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | 生成一个有识别注解能力的插件类别
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | 生成一个有识别Yaml能力的插件类别
[generate:plugin:views:field](generate-plugin-views-field.md) | 生成一个定制的插件视窗域.
[generate:profile](generate-profile.md) | 生成一个方案.
[generate:routesubscriber](generate-routesubscriber.md) | 生成一个路径订阅
[generate:service](generate-service.md) | 生成服务
[generate:theme](generate-theme.md) | 生成一个外观主题.
**image**  |
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | commands.libraries.debug.description
**locale**  |
[locale:language:add](locale-language-add.md) | 添加一种语言
[locale:language:delete](locale-language-delete.md) | 删除一种语言
[locale:translation:status](locale-translation-status.md) | 列出可用翻译更新
**migrate**  |
[migrate:debug](migrate-debug.md) | 显示当前可用迁移
[migrate:execute](migrate-execute.md) | 执行可用迁移
[migrate:setup](migrate-setup.md) | 导入或创建数据库迁移
**module**  |
[module:debug](module-debug.md) | 显示当前可用模块
[module:download](module-download.md) | 下载模块
[module:install](module-install.md) | 安装模块
[module:uninstall](module-uninstall.md) | 卸载模块
**multisite**  |
[multisite:debug](multisite-debug.md) | 列出所有可用多站点
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**rest**  |
[rest:debug](rest-debug.md) | 显示当前 REST 资源
[rest:disable](rest-disable.md) | 禁用 REST 资源
[rest:enable](rest-enable.md) | 启用 REST 资源
**router**  |
[router:debug](router-debug.md) | 显示路由
[router:rebuild](router-rebuild.md) | 重建路由
**settings**  |
[settings:debug](settings-debug.md) | 列出用户Drupal控制台设置.
[settings:set](settings-set.md) | 改变 DrupalConsole 配置文件中的配置
**site**  |
[site:debug](site-debug.md) | 列出已知当地和远程网站.
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | 安装 Drupal
[site:maintenance](site-maintenance.md) | 切换网站到维护模式
[site:mode](site-mode.md) | 转换系统性能配置
[site:new](site-new.md) | 生成一个新的Drupal项目
[site:statistics](site-statistics.md) | 显示网站的当前统计
[site:status](site-status.md) | 当前Drupal安装状态
**state**  |
[state:debug](state-debug.md) | 显示当前状态的键(s)
[state:delete](state-delete.md) | 删除状态
[state:override](state-override.md) | 覆写状态键的值
**test**  |
[test:debug](test-debug.md) | 列出可用的程序测试.
[test:run](test-run.md) | 运行这个程序有的测试单元
**theme**  |
[theme:debug](theme-debug.md) | 显示当前主题
[theme:download](theme-download.md) | 下载主题
[theme:install](theme-install.md) | 安装主题
[theme:uninstall](theme-uninstall.md) | 卸载程序的一个或多个外观主题
**translation**  |
[translation:cleanup](translation-cleanup.md) | 清理翻译文件
[translation:pending](translation-pending.md) | 未翻译检测
[translation:stats](translation-stats.md) | 生成翻译统计
[translation:sync](translation-sync.md) | 同步翻译文件
**update**  |
[update:debug](update-debug.md) | 显示目前有的程序更新
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | 执行的给出的某个模块的更新程序或者执行所有的更新程序
**user**  |
[user:debug](user-debug.md) | 显示网站的当前用户(s)
[user:delete](user-delete.md) | 删除网站用户(s)
[user:login:clear:attempts](user-login-clear-attempts.md) | 清空一个用户的登录尝试数据。
[user:login:url](user-login-url.md) | 返回一次性登录链接.
[user:password:hash](user-password-hash.md) | 从文本格式密码中生成哈希码
[user:password:reset](user-password-reset.md) | 为指定用户重设密码.
**views**  |
[views:debug](views-debug.md) | 显示网站当前视图资源
[views:disable](views-disable.md) | 停启视图
[views:enable](views-enable.md) | 启用一个视图
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | 比较两个YAML文件找出区别
[yaml:merge](yaml-merge.md) | 合并一个或多个YAML文件. 如键值有冲突，取最新值.
[yaml:split](yaml-split.md) | 根据缩进分开YAML文件
[yaml:update:key](yaml-update-key.md) | 替换 YAML 文件中一个键本身的值
[yaml:update:value](yaml-update-value.md) | 更新 YAML 文件中的指定键对应的值

## 可用选项
选项 | 详细
-------|-------------
--help | 显示这个帮助信息
--quiet | 不显示任何帮助信息
--verbose | 输出信息控制: 1 普通输出, 2 详细输出 and 3 调试信息输出
--version | <info>%s</info> 版本 <comment>%s</comment>
--ansi | 强制 ANSI 输出
--no-ansi | 禁用 ANSI 输出
--no-interaction | 非交互式
--env | 环境名称
--root | 定义 Drupal 根目录，命令执行时使用
--no-debug | 禁用调试
--learning | 生成详细的代码输出用于学习
--generate-chain | 以 YAML 格式显示命令执行时的选项和参数，用于链式执行一组命令
--generate-inline | 将命令执行时的选项和参数显示成一行，以便后续使用
--generate-doc | 显示命令选项和参数为 markdown 格式
--target | 与之交互的站点名字（本地或远程网站）
--uri | Drupal 网站的 URI( 用于多站点环境或运行在不同的端口)
--yes | 跳过确认并继续

## 可用参数
参数 | 详细
---------|-------------
command | 要执行的命令
