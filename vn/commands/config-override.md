# config:override
Ghi đè giá trị cấu hình trong cấu hình đang hoạt động

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Configuration name
key | Khóa
value | Giá trị

## application.gitbook.messages.examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
