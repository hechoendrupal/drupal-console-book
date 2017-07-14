# create:users
ダミーのユーザーを作成

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | 作成するユーザーの数
--password | 作成したユーザーのパスワード
--time-range | ユーザーの作成時刻

## Available arguments
Argument | Details
---------|-------------
roles | 作成するユーザーのロール (複数指定可)

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
