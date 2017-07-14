# config:edit
Редактирование выбранной конфигурации.

**Usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## Available arguments
Argument | Details
---------|-------------
config-name | Имя конфигурации.
editor | Редактор.

## Examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
