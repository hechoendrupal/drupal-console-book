# create:users
生成用户

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | 生成多少个用户
--password | 用户密码
--time-range | 用户的创建时间范围

## Available arguments
Argument | Details
---------|-------------
roles | 用于生成用户的角色(s)

## Examples
* Provide the user role.
```
drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
