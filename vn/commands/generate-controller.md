# generate:controller
Tạo và đăng ký một trình điều khiển

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:controller [options]
$ gcn  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | Tên module.
--class | Tên lớp của trình điều khiển
--routes | The routes, must be an array containing [title, method, path]
--services | Nạp các dịch vụ từ container.
--test | Tạo một lớp thử nghiệm
