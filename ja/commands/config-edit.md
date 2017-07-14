# config:edit
設定を編集する

**Usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## Available arguments
Argument | Details
---------|-------------
config-name | 設定の名前
editor | 編集に使用するエディタ

## Examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
