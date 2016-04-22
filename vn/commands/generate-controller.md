# generate:controller
Tạo và đăng ký một trình điều khiển

**Usage:**
```
$ drupal generate:controller [options]
$ gcn  
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--module | Tên module.
--class | Tên lớp của trình điều khiển
--routes | The routes, must be an array containing [title, method, path]
--services | Nạp các dịch vụ từ container.
--test | Tạo một lớp thử nghiệm
