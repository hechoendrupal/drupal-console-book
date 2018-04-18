# generate:command
生成新 Console 命令

**使用方法:**
```
drupal generate:command [options]
gco
```

## 可用选项
选项 | 详细信息
-------|-------------
--extension | 扩展名。
--extension-type | 扩展类型。
--class | 命令类名
--name | 命令名称
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | 这条命令需要在 Drupal 网站所在目录里执行吗？
--services | 从容器加载服务。
--generator | Add a Generator class for this command.

## 例子
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
