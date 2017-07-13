# config:edit
Chỉnh sửa cấu hình đã được chọn

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:edit [arguments]
$ ced  
$ cdit  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
config-name | Tên cấu hình
editor | Editor.

## commands.generate.doc.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
$ drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
$ drupal config:edit system.cron gedit
```
