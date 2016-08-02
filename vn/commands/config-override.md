# config:override
Ghi đè giá trị cấu hình trong cấu hình đang hoạt động

**Usage:**
```
$ drupal config:override [arguments]
$ co  
```

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
name | Configuration name
key | Khóa
value | Giá trị

## Ví dụ
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
