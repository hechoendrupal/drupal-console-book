# config:edit
선택한 설정을 수정합니다.

**application.gitbook.messages.usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
config-name | 설정명.
editor | 편집기.

## application.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```
