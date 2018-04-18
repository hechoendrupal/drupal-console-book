# generate:command
Tạo ra các lệnh cho trình điều khiển.

**Usage:**
```
drupal generate:command [options]
gco
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | Lớp miêu tả dòng lện. (Phải kết thúc bằng từ 'Commmand').
--name | Tên dòng lệnh.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | Dòng lệnh có nhận thức được sự cài đặt drupal site khi thực hiện hay không
--services | Nạp các dịch vụ từ container.
--generator | Add a Generator class for this command.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
