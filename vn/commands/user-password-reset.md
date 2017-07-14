# user:password:reset
Đặt lại mật khẩu cho một người dùng cụ thể.

**Usage:**
```
drupal user:password:reset [arguments]
upr
uspr
```

## Available arguments
Argument | Details
---------|-------------
user | ID người dùng
password | Mật khẩu có định dạng text

## Examples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
