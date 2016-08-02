# Các lệnh điều khiển Drupal có sẵn

**Note:** Các lệnh điều khiển Drupal *phải* được chạy từ root của sự cài đặt Drupal 8.

Các lệnh điều khiển Drupal | Các chi tiết
------------ | -------------
[about](about.md) | Hiển thị thông tin cơ bản về dự án Drupal Console
[chain](chain.md) | Thi hành chuỗi câu lệnh
[check](check.md) | System requirement checker
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Các danh sách tất cả các dòng lệnh có sẵn
[self-update](self-update.md) | Update project to the latest version.
[server](server.md) | Chạy PHP built-in web server
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | Displays breakpoints available in application
**cache**  |
[cache:context:debug](cache-context-debug.md) | Displays current cache context for the application.
[cache:rebuild](cache-rebuild.md) | Xây dựng lại và làm sạch tất cả cache trên trang.
**chain**  |
[chain:debug](chain-debug.md) | List available chain files.
**config**  |
[config:debug](config-debug.md) | Hiển thị cấu hình hiện tại
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Chỉnh sửa cấu hình đã được chọn
[config:export](config-export.md) | Xuất cấu hình ứng dụng hiện tại
[config:export:content:type](config-export-content-type.md) | Xuất một kiểu nội dung chỉ định và các field của chúng
[config:export:view](config-export-view.md) | Export 1 view trong YAML format inside 1 module được cung cấp để sử dụng lại trên các website khác.
[config:import](config-import.md) | Nhập cấu hình tới ứng dụng hiện tại
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Ghi đè giá trị cấu hình trong cấu hình đang hoạt động
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
**container**  |
[container:debug](container-debug.md) | Các dịch vụ hiển thị hiện tại cho một ứng dụng
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Tạo dummy nodes cho ứng dụng Drupal 8 của bạn.
[create:terms](create-terms.md) | Tạo dummy terms cho ứng dụng Drupal 8 của bạn.
[create:users](create-users.md) | Tạo dummy users cho ứng dụng Drupal 8 của bạn.
[create:vocabularies](create-vocabularies.md) | Tạo dummy vocabularies cho ứng dụng Drupal 8 của bạn.
**cron**  |
[cron:debug](cron-debug.md) | Danh sách của các module đang thực hiện một lệnh cron
[cron:execute](cron-execute.md) | Thi hành cron implementation từ một module chỉ định hoặc tất cả để thực thi tất cả các lệnh thi hành
[cron:release](cron-release.md) | Giải phóng khoá cron hệ thống để cho phép chạy lại cron
**database**  |
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Hiển thị DB connection
[database:drop](database-drop.md) | Drop tất cả các tables trong 1 cơ sở dữ liệu được đưa ra.
[database:dump](database-dump.md) | Dump cấu trúc và nội dung của 1 cơ sở dữ liệu
[database:log:clear](database-log-clear.md) | Xóa các sự kiện từ DBLog table, filters là có thể sử dụng được
[database:log:debug](database-log-debug.md) | Hiển thị các dấu sự kiện hiện tại cho ứng dụng
[database:restore](database-restore.md) | Khôi phục cấu trúc và content của một cơ sở dữ liệu
[database:table:debug](database-table-debug.md) | Hiển thị tất cả các bảng trong database đã được cung cấp.
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**event**  |
[event:debug](event-debug.md) | Display current events 
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | Generate the DrupalConsole.docset package for Dash
[generate:doc:data](generate-doc-data.md) | Generate documentations for Commands.
[generate:doc:gitbook](generate-doc-gitbook.md) | Generate documentations for Commands
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
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | Displays libraries available in application
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | Hiển thị phần chuyển đổi dữ liệu hiện có cho ứng dựng
[migrate:execute](migrate-execute.md) | Tiến hành một phần chuyển đổi dữ liệu có sẵn trong ứng dụng
**module**  |
[module:debug](module-debug.md) | Hiển thị các module hiện có cho ứng dụng
[module:download](module-download.md) | Tải module hoặc các modules trong ứng dụng
[module:install](module-install.md) | Cài đặt module hoặc các module trong ứng dụng
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Gỡ bỏ module hoặc các module trong ứng dụng
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | Liệt kê tất cả các multisites đang có sẵn trong hệ thống
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**queue**  |
[queue:debug](queue-debug.md) | Display the queues of your application
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:debug](rest-debug.md) | Hiển thị rest resource hiện có cho ứng dụng
[rest:disable](rest-disable.md) | Tắt một tài nguyên rest cho ứng dụng
[rest:enable](rest-enable.md) | Bật một rest resource cho ứng dụng
**router**  |
[router:debug](router-debug.md) | Hiển thị các định tuyến hiện tại của ứng dụng
[router:rebuild](router-rebuild.md) | Xây dựng lại định tuyến cho ứng dụng
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Liệt kê tất cả các sites cục bộ và từ xa đã biết.
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Cài đặt một dự án Drupal
[site:maintenance](site-maintenance.md) | Chuyển site sang chế độ bảo trì
[site:mode](site-mode.md) | Chuyển đổi cấu hình hiệu năng của hệ thống
[site:new](site-new.md) | Tạo một dự án Drupal mới
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Xem trạng thái cài đặt hiện tại
**state**  |
[state:debug](state-debug.md) | Hiển thị State keys hiện tại.
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Ghi đè một State key.
**test**  |
[test:debug](test-debug.md) | Danh sách các đơn vị thử nghiệm có sẵn của ứng dụng.
[test:run](test-run.md) | Chạy đơn vị thử nghiệm từ các thử nghiệm có sẵn cho ứng dụng
**theme**  |
[theme:debug](theme-debug.md) | Hiển thị các themes hiện tại cho ứng dụng
[theme:download](theme-download.md) | Tải xuống theme trong ứng dụng
[theme:install](theme-install.md) | Cài đặt theme hoặc các themes trong ứng dụng
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Gỡ cài đặt theme hay các themes trong ứng dụng
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clean up translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Hiển thị các cập nhật có sẵn cho ứng dụng
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Tiến hành một hàm cụ thể cập nhật N trong một module, hoặc tiến hành tất cả
**user**  |
[user:debug](user-debug.md) | Hiển thị các người dùng hiện tại cho ứng dụng
[user:delete](user-delete.md) | Xóa người dùng cho ứng dụng
[user:login:clear:attempts](user-login-clear-attempts.md) | Xóa các đăng nhập thử không thành công cho một tài khoản.
[user:login:url](user-login-url.md) | Quay lại một url đăng nhập của người dùng một lần.
[user:password:hash](user-password-hash.md) | Tạo một hash từ một mật khẩu thô
[user:password:reset](user-password-reset.md) | Đặt lại mật khẩu cho một người dùng cụ thể.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:debug](views-debug.md) | Hiển thị các views resources hiện tại cho ứng dụng
[views:disable](views-disable.md) | Tắt một View
[views:enable](views-enable.md) | Bật một View
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | So sánh hai files YAML để xác định sự khác nhau giữa chúng
[yaml:merge](yaml-merge.md) | Merge một hoặc nhiều files YAML vào trong một file YAML mới. Giá trị mới nhất được duy trì.
[yaml:split](yaml-split.md) | Tách một file YAML sử dụng indent là tiêu chí phân tách
[yaml:update:key](yaml-update-key.md) | Thay thế một key YAML trong một file YAML.
[yaml:update:value](yaml-update-value.md) | Cập nhật một giá trị cho một key cụ thể trong file YAML.

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
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
--no-debug | Tắt chế độ debug
--learning | Sinh ra chi tiết mã thực thi
--generate-chain | In các lựa chọn thi hành và các đối số dạng yaml, để sử dụng trong chuỗi lệnh
--generate-inline | In các lựa chọn thi hành và các đối số dạng inline, để sử dụng sau
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | Đường dẫn site Drupal được dùng (cho môi trường multisite hoặc khi chạy trên một cổng thay thế)
--yes | Skip confirmation and proceed

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
command | The command to execute
