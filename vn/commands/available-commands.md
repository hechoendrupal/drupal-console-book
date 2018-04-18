# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Hiển thị thông tin cơ bản về dự án Drupal Console
[chain](chain.md) | Thi hành chuỗi câu lệnh
[check](check.md) | System requirement checker
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Execute an external command.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Các danh sách tất cả các dòng lệnh có sẵn
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Chạy PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Xây dựng lại và làm sạch tất cả cache trên trang.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Chỉnh sửa cấu hình đã được chọn
[config:export](config-export.md) | Xuất cấu hình ứng dụng hiện tại
[config:export:content:type](config-export-content-type.md) | Xuất một kiểu nội dung chỉ định và các field của chúng
[config:export:single](config-export-single.md) | Xuất cấu hình đơn giản như yml file
[config:export:view](config-export-view.md) | Export 1 view trong YAML format inside 1 module được cung cấp để sử dụng lại trên các website khác.
[config:import](config-import.md) | Nhập cấu hình tới ứng dụng hiện tại
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Ghi đè giá trị cấu hình trong cấu hình đang hoạt động
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Tạo dummy nodes cho ứng dụng Drupal 8 của bạn.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | Tạo dummy terms cho ứng dụng Drupal 8 của bạn.
[create:users](create-users.md) | Tạo dummy users cho ứng dụng Drupal 8 của bạn.
[create:vocabularies](create-vocabularies.md) | Tạo dummy vocabularies cho ứng dụng Drupal 8 của bạn.
**cron**  |
[cron:execute](cron-execute.md) | Thi hành cron implementation từ một module chỉ định hoặc tất cả để thực thi tất cả các lệnh thi hành
[cron:release](cron-release.md) | Giải phóng khoá cron hệ thống để cho phép chạy lại cron
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Hiển thị DB connection
[database:drop](database-drop.md) | Drop tất cả các tables trong 1 cơ sở dữ liệu được đưa ra.
[database:dump](database-dump.md) | Dump cấu trúc và nội dung của 1 cơ sở dữ liệu
[database:log:clear](database-log-clear.md) | Xóa các sự kiện từ DBLog table, filters là có thể sử dụng được
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Khôi phục cấu trúc và content của một cơ sở dữ liệu
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | List available chain files.
[debug:config](debug-config.md) | Hiển thị cấu hình hiện tại
[debug:config:settings](debug-config-settings.md) | Displays current key:value on settings file.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Các dịch vụ hiển thị hiện tại cho một ứng dụng
[debug:cron](debug-cron.md) | Danh sách của các module đang thực hiện một lệnh cron
[debug:database:log](debug-database-log.md) | Hiển thị các dấu sự kiện hiện tại cho ứng dụng
[debug:database:table](debug-database-table.md) | Hiển thị tất cả các bảng trong database đã được cung cấp.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Hiển thị phần chuyển đổi dữ liệu hiện có cho ứng dựng
[debug:module](debug-module.md) | Hiển thị các module hiện có cho ứng dụng
[debug:multisite](debug-multisite.md) | Liệt kê tất cả các multisites đang có sẵn trong hệ thống
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Hiển thị rest resource hiện có cho ứng dụng
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | Hiển thị các định tuyến hiện tại của ứng dụng
[debug:settings](debug-settings.md) | List user Drupal Console settings.
[debug:site](debug-site.md) | Liệt kê tất cả các sites cục bộ và từ xa đã biết.
[debug:state](debug-state.md) | Hiển thị State keys hiện tại.
[debug:test](debug-test.md) | Danh sách các đơn vị thử nghiệm có sẵn của ứng dụng.
[debug:theme](debug-theme.md) | Hiển thị các themes hiện tại cho ứng dụng
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | Hiển thị các cập nhật có sẵn cho ứng dụng
[debug:user](debug-user.md) | Hiển thị các người dùng hiện tại cho ứng dụng
[debug:views](debug-views.md) | Hiển thị các views resources hiện tại cho ứng dụng
[debug:views:plugins](debug-views-plugins.md) | Display current views plugins for the application
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
[generate:authentication:provider](generate-authentication-provider.md) | Tạo ra một Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Tạo ra các lệnh cho trình điều khiển.
[generate:controller](generate-controller.md) | Tạo và đăng ký một trình điều khiển
[generate:entity:bundle](generate-entity-bundle.md) | Tạo một loại nội dung mới (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Tạo một config entity mới
[generate:entity:content](generate-entity-content.md) | Tạo một content entity mới
[generate:event:subscriber](generate-event-subscriber.md) | Tạo một event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Tạo một implementation của hook_form_alter() hoặc hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Tạo một module.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Tạo một plugin block
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Tạo một plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Tạo field type, widget và formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Tạo một formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Tạo field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Tạo field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Tạo plugin hiệu ứng hình ảnh
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Phát sinh một image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Tạo plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Tạo một plugin rule action
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Tạo một kiểu plugin với annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Tạo một plugin với Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Tạo một tùy chỉnh plugin view field.
[generate:post:update](generate-post-update.md) | Generate an implementation of hook_post_update_NAME()
[generate:profile](generate-profile.md) | Tạo một profile.
[generate:routesubscriber](generate-routesubscriber.md) | Tạo một RouteSubscriber
[generate:service](generate-service.md) | Tạo dịch vụ
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Tạo một theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Thêm một ngôn ngữ được hỗ trợ bởi site của bạn
[locale:language:delete](locale-language-delete.md) | Xóa một ngôn ngữ được hỗ trợ bởi site cuuar bạn
[locale:translation:status](locale-translation-status.md) | Danh sách cập nhật bản dịch có sẵn
**migrate**  |
[migrate:execute](migrate-execute.md) | Tiến hành một phần chuyển đổi dữ liệu có sẵn trong ứng dụng
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | Tải module hoặc các modules trong ứng dụng
[module:install](module-install.md) | Cài đặt module hoặc các module trong ứng dụng
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Gỡ bỏ module hoặc các module trong ứng dụng
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:disable](rest-disable.md) | Tắt một tài nguyên rest cho ứng dụng
[rest:enable](rest-enable.md) | Bật một rest resource cho ứng dụng
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | Xây dựng lại định tuyến cho ứng dụng
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Cài đặt một dự án Drupal
[site:maintenance](site-maintenance.md) | Chuyển site sang chế độ bảo trì
[site:mode](site-mode.md) | Chuyển đổi cấu hình hiệu năng của hệ thống
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Xem trạng thái cài đặt hiện tại
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Ghi đè một State key.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Chạy đơn vị thử nghiệm từ các thử nghiệm có sẵn cho ứng dụng
**theme**  |
[theme:download](theme-download.md) | Tải xuống theme trong ứng dụng
[theme:install](theme-install.md) | Cài đặt theme hoặc các themes trong ứng dụng
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Gỡ cài đặt theme hay các themes trong ứng dụng
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Tiến hành một hàm cụ thể cập nhật N trong một module, hoặc tiến hành tất cả
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Xóa người dùng cho ứng dụng
[user:login:clear:attempts](user-login-clear-attempts.md) | Xóa các đăng nhập thử không thành công cho một tài khoản.
[user:login:url](user-login-url.md) | Quay lại một url đăng nhập của người dùng một lần.
[user:password:hash](user-password-hash.md) | Tạo một hash từ một mật khẩu thô
[user:password:reset](user-password-reset.md) | Đặt lại mật khẩu cho một người dùng cụ thể.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Tắt một View
[views:enable](views-enable.md) | Bật một View

## Available options
Option | Details
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | <info>"%s"</info> version <comment>"%s"</comment>
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | Tên môi trường
--root | Định nghĩa Drupal root dùng để thực thi lệnh
--debug | Switches on debug mode
--learning | Sinh ra chi tiết mã thực thi
--generate-chain | In các lựa chọn thi hành và các đối số dạng yaml, để sử dụng trong chuỗi lệnh
--generate-inline | In các lựa chọn thi hành và các đối số dạng inline, để sử dụng sau
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | Đường dẫn site Drupal được dùng (cho môi trường multisite hoặc khi chạy trên một cổng thay thế)
--yes | Skip confirmation and proceed

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
