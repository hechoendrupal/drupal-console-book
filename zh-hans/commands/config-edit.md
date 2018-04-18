# config:edit
使用文本编辑器更改配置对象。

**使用方法:**
```
drupal config:edit [arguments]
ced
cdit
```

## 可用参数
参数 | 详细信息
---------|-------------
config-name | 配置对象名称，例如 "user.settings"。
editor | 编辑器，例如 "vim" 或 "gedit"。

## 例子
* 使用 "vim"（默认编辑器）编辑系统 cron 配置。
```
drupal config:edit system.cron
```
* 使用用 "gedit" 编辑系统 cron 配置。
```
drupal config:edit system.cron gedit
```
