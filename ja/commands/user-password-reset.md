# user:password:reset
指定したユーザーのパスワードをリセットする

**Usage:**
```
drupal user:password:reset [arguments]
upr
uspr
```

## Available arguments
Argument | Details
---------|-------------
user | ユーザーID
password | プレーンテキストのパスワード

## Examples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
