# config:override
Ghi đè giá trị cấu hình trong cấu hình đang hoạt động

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:override [arguments]
$ co  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | Configuration name
key | Khóa
value | Giá trị

## commands.generate.doc.gitbook.messages.examples
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
