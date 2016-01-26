# Các lệnh điều khiển Drupal có sẵn

**Note:** Các lệnh điều khiển Drupal *phải* được chạy từ root của sự cài đặt Drupal 8.

Các lệnh điều khiển Drupal | Các chi tiết
------------ | -------------
[about](about.md) | Hiển thị thông tin cơ bản về dự án Drupal Console
[chain](chain.md) | Thi hành chuỗi câu lệnh
[help](help.md) | Displays help for a command
[init](init.md) | Sao chép các file cấu hình tới thư mục gốc.
[list](list.md) | Các danh sách tất cả các dòng lệnh có sẵn
[server](server.md) | Chạy PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Xây dựng lại và làm sạch tất cả cache trên trang.
**config**  |
[config:debug](config-debug.md) | Hiển thị cấu hình hiện tại
[config:edit](config-edit.md) | Chỉnh sửa cấu hình đã được chọn
[config:export](config-export.md) | Xuất cấu hình ứng dụng hiện tại
[config:export:content:type](config-export-content-type.md) | Xuất một kiểu nội dung chỉ định và các field của chúng
[config:export:single](config-export-single.md) | Xuất cấu hình đơn giản như yml file
[config:export:view](config-export-view.md) | Export 1 view trong YAML format inside 1 module được cung cấp để sử dụng lại trên các website khác.
[config:import](config-import.md) | Nhập cấu hình tới ứng dụng hiện tại
[config:import:single](config-import-single.md) | Import cấu hình đã được chọn.
[config:override](config-override.md) | Ghi đè giá trị cấu hình trong cấu hình đang hoạt động
**container**  |
[container:debug](container-debug.md) | Các dịch vụ hiển thị hiện tại cho một ứng dụng
**create**  |
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
[database:dump](database-dump.md) | Dump cấu trúc và nội dung của 1 cơ sở dữ liệu
[database:log:clear](database-log-clear.md) | Xóa các sự kiện từ DBLog table, filters là có thể sử dụng được
[database:log:debug](database-log-debug.md) | Hiển thị các dấu sự kiện hiện tại cho ứng dụng
[database:restore](database-restore.md) | Khôi phục cấu trúc và content của một cơ sở dữ liệu
[database:table:debug](database-table-debug.md) | Hiển thị tất cả các bảng trong database đã được cung cấp.
[database:table:drop](database-table-drop.md) | Drop tất cả các tables trong 1 cơ sở dữ liệu được đưa ra.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Tạo ra một Authentication Provider
[generate:command](generate-command.md) | Tạo ra các lệnh cho trình điều khiển.
[generate:controller](generate-controller.md) | Tạo và đăng ký một trình điều khiển
[generate:doc:dash](generate-doc-dash.md) | Tạo gói DrupalConsole.docset cho Dash
[generate:doc:gitbook](generate-doc-gitbook.md) | Tạo documentations cho các lệnh
[generate:entity:bundle](generate-entity-bundle.md) | Tạo một loại nội dung mới (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Tạo một config entity mới
[generate:entity:content](generate-entity-content.md) | Tạo một content entity mới
[generate:event:subscriber](generate-event-subscriber.md) | Tạo một event subscriber
[generate:form](generate-form.md) | Tạo một "FormBase" mới
[generate:form:alter](generate-form-alter.md) | Tạo một implementation của hook_form_alter() hoặc hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Tạo một "ConfigFormBase" mới
[generate:module](generate-module.md) | Tạo một module.
[generate:permissions](generate-permissions.md) | Tạo module permissions
[generate:plugin:block](generate-plugin-block.md) | Tạo một plugin block
[generate:plugin:condition](generate-plugin-condition.md) | Tạo một plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Tạo field type, widget và formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Tạo một formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Tạo field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Tạo field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Tạo plugin hiệu ứng hình ảnh
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Phát sinh một image formatter plugin.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Tạo plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Tạo một plugin rule action
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Tạo một kiểu plugin với annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Tạo một plugin với Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Tạo một tùy chỉnh plugin view field.
[generate:profile](generate-profile.md) | Tạo một profile.
[generate:routesubscriber](generate-routesubscriber.md) | Tạo một RouteSubscriber
[generate:service](generate-service.md) | Tạo dịch vụ
[generate:theme](generate-theme.md) | Tạo một theme.
**locale**  |
[locale:language:add](locale-language-add.md) | Thêm một ngôn ngữ được hỗ trợ bởi site của bạn
[locale:language:delete](locale-language-delete.md) | Xóa một ngôn ngữ được hỗ trợ bởi site cuuar bạn
[locale:translation:status](locale-translation-status.md) | Danh sách cập nhật bản dịch có sẵn
**migrate**  |
[migrate:debug](migrate-debug.md) | Hiển thị phần chuyển đổi dữ liệu hiện có cho ứng dựng
[migrate:execute](migrate-execute.md) | Tiến hành một phần chuyển đổi dữ liệu có sẵn trong ứng dụng
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:debug](module-debug.md) | Hiển thị các module hiện có cho ứng dụng
[module:download](module-download.md) | Tải module hoặc các modules trong ứng dụng
[module:install](module-install.md) | Cài đặt module hoặc các module trong ứng dụng
[module:uninstall](module-uninstall.md) | Gỡ bỏ module hoặc các module trong ứng dụng
**multisite**  |
[multisite:debug](multisite-debug.md) | Liệt kê tất cả các multisites đang có sẵn trong hệ thống
**rest**  |
[rest:debug](rest-debug.md) | Hiển thị rest resource hiện có cho ứng dụng
[rest:disable](rest-disable.md) | Tắt một tài nguyên rest cho ứng dụng
[rest:enable](rest-enable.md) | Bật một rest resource cho ứng dụng
**router**  |
[router:debug](router-debug.md) | Hiển thị các định tuyến hiện tại của ứng dụng
[router:rebuild](router-rebuild.md) | Xây dựng lại định tuyến cho ứng dụng
**settings**  |
[settings:debug](settings-debug.md) | Displays current key:value on settings file.
**site**  |
[site:debug](site-debug.md) | Liệt kê tất cả các sites cục bộ và từ xa đã biết.
[site:install](site-install.md) | Cài đặt một dự án Drupal
[site:maintenance](site-maintenance.md) | Chuyển site sang chế độ bảo trì
[site:mode](site-mode.md) | Chuyển đổi cấu hình hiệu năng của hệ thống
[site:new](site-new.md) | Tạo một dự án Drupal mới
[site:status](site-status.md) | Xem trạng thái cài đặt hiện tại
**state**  |
[state:debug](state-debug.md) | Hiển thị State keys hiện tại.
[state:override](state-override.md) | Ghi đè một State key.
**test**  |
[test:debug](test-debug.md) | Danh sách các đơn vị thử nghiệm có sẵn của ứng dụng.
[test:run](test-run.md) | Chạy đơn vị thử nghiệm từ các thử nghiệm có sẵn cho ứng dụng
**theme**  |
[theme:debug](theme-debug.md) | Hiển thị các themes hiện tại cho ứng dụng
[theme:download](theme-download.md) | Tải xuống theme trong ứng dụng
[theme:install](theme-install.md) | Cài đặt theme hoặc các themes trong ứng dụng
[theme:uninstall](theme-uninstall.md) | Gỡ cài đặt theme hay các themes trong ứng dụng
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clenaup translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Hiển thị các cập nhật có sẵn cho ứng dụng
[update:execute](update-execute.md) | Tiến hành một hàm cụ thể cập nhật N trong một module, hoặc tiến hành tất cả
**user**  |
[user:debug](user-debug.md) | Hiển thị các người dùng hiện tại cho ứng dụng
[user:delete](user-delete.md) | Xóa người dùng cho ứng dụng
[user:login:clear:attempts](user-login-clear-attempts.md) | Xóa các đăng nhập thử không thành công cho một tài khoản.
[user:login:url](user-login-url.md) | Quay lại một url đăng nhập của người dùng một lần.
[user:password:hash](user-password-hash.md) | Tạo một hash từ một mật khẩu thô
[user:password:reset](user-password-reset.md) | Đặt lại mật khẩu cho một người dùng cụ thể.
**views**  |
[views:debug](views-debug.md) | Hiển thị các views resources hiện tại cho ứng dụng
[views:disable](views-disable.md) | Tắt một View
[views:enable](views-enable.md) | Bật một View
**yaml**  |
[yaml:diff](yaml-diff.md) | So sánh hai files YAML để xác định sự khác nhau giữa chúng
[yaml:merge](yaml-merge.md) | Merge một hoặc nhiều files YAML vào trong một file YAML mới. Giá trị mới nhất được duy trì.
[yaml:split](yaml-split.md) | Tách một file YAML sử dụng indent là tiêu chí phân tách
[yaml:update:key](yaml-update-key.md) | Thay thế một key YAML trong một file YAML.
[yaml:update:value](yaml-update-value.md) | Cập nhật một giá trị cho một key cụ thể trong file YAML.

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--help | Hiển thị thông báo giúp đỡ
--quiet | Đừng đưa ra bất cứ thông báo nào
--verbose | Tăng độ dài của các thông báo: 1 cho đầu ra thông thường, 2 cho những đầu ra dài hơn và 3 cho tìm kiếm lỗi
--version | Hiển thị phiên bản ứng dụng
--ansi | hiệu lực ANSI đầu ra
--no-ansi | Tắt ANSI đầu ra
--no-interaction | Đừng yêu cầu bất kỳ câu hỏi tương tác nào
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
command | Câu lệnh để thực thi
