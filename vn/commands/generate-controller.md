# generate:controller
Tạo và đăng ký một trình điều khiển

**application.gitbook.messages.usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Tên module.
--class | Tên lớp của trình điều khiển
--routes | The routes, must be an array containing [title, method, path]
--services | Nạp các dịch vụ từ container.
--test | Tạo một lớp thử nghiệm
