# generate:command
Tạo ra các lệnh cho trình điều khiển.

**application.gitbook.messages.usage:**
```
drupal generate:command [options]
gco
gcm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | Lớp miêu tả dòng lện. (Phải kết thúc bằng từ 'Commmand').
--name | Tên dòng lệnh.
--container-aware | Dòng lệnh có nhận thức được sự cài đặt drupal site khi thực hiện hay không
--services | Nạp các dịch vụ từ container.
