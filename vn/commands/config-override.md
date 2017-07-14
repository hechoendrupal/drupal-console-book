# config:override
Ghi đè giá trị cấu hình trong cấu hình đang hoạt động

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration name
key | Khóa
value | Giá trị

## Examples
* Définir la valeur de "flood" du module Contact à 10.
```
drupal config:override contact.settings flood.limit 10
```
