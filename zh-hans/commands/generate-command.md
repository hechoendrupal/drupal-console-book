# generate:command
生成新 Console 命令

**Usage:**
```
drupal generate:command [options]
gco
gcm
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | 命令类名
--name | 命令名称
--container-aware | 这条命令需要在 Drupal 网站所在目录里执行吗？
--services | 从容器中导入服务

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
